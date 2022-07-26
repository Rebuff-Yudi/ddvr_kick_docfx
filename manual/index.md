## Create the track and data type

First you need to create custom data type for your track, create new class that inherit from @RhythmTool.Feature ,

then create a new class inherit from <xref:RhythmTool.Track`1> where T should be the custom data type you just created.

## Create the editor GUI for newly created track

Create a new class inside 'Editor' folder inherit from <xref:RhythmTool.FeatureGUI`1> where T should be the custom data type you just created.

## Make sure newly generated beat-map will contain this track

Go to @RhythmTool.EditorAnalyzer.CreateBeatmap and add your newly created track accordingly.

## Hook up with event provider

Use <xref:RhythmTool.RhythmEventProvider.Register``1(Action{``0})> and <xref:RhythmTool.RhythmEventProvider.Unregister``1(Action{``0})> to link event callback to the music timeline pointer event so the note generator could generate note using the newly created track and its data.