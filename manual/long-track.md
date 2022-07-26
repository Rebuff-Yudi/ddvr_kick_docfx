## Long note track

![long-note-track](/resources/long-note-track.png)

Long note track contain 4 track types (see @RhythmTool.LongNote.track ). Each could be assign to different or same path according to @DDVRKick.Tracks.TracksManager.longNoteTracks .

## Long note data

![long-note-data](/resources/long-note-data.png)

Each long note should use its length property to dynamically adjust its length according to the note speed, (see @DDVRKick.Tracks.LongNoteTrack.GenerateLongNote(RhythmTool.LongNote) ) 

For functions in unity editor should checkout @RhythmTool.LongNoteGUI .