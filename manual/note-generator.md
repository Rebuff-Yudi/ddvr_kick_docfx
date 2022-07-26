# Tracks manager

The @DDVRKick.Tracks.TracksManager manage all tracks and paths.

![track-manager](/resources/note-generator.png)

It needs an @RhythmTool.RhythmEventProvider and an @RhythmTool.RhythmPlayer to sync up with music timeline.

The @RhythmTool.RhythmEventProvider.offset should match up the time it takes for one note travel from the beginning of the path to the end of the path.

For note generation, it uses <xref:RhythmTool.RhythmEventProvider.Register``1(Action{``0})> and <xref:RhythmTool.RhythmEventProvider.Unregister``1(Action{``0})> to link event callback to the music timeline pointer event.

Check @DDVRKick.Tracks.TracksManager.Start and @DDVRKick.Tracks.TracksManager.OnDestroy for usage example.