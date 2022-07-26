## Lower note track

![lower-note-track](../resources/lower-note-track.png)

(see @RhythmTool.LowerNoteTrack and @RhythmTool.LowerNoteTrackGUI )

The lower layer of note tracks contain 4 different path type (see @RhythmTool.LowerNoteData.pathType ),
each can be map to different or same path according to (see @DDVRKick.Tracks.TracksManager.lowerTracks ).

![lower-note-data](../resources/lower-note-data.png)

(see @RhythmTool.LowerNoteData )

This note should only use its timestamp to map its own position on the song timeline.

## Upper note track

![upper-note-track](../resources/upper-note-track.png)

(see @RhythmTool.UpperNoteTrack and @RhythmTool.UpperNoteTrackGUI )

The upper layer of note tracks contain 4 different path type (see @RhythmTool.UpperNoteData.pathType ),
each can be map to different or same path according to (see @DDVRKick.Tracks.TracksManager.upperTracks ).

![upper-note-data](../resources/upper-note-data.png)

(see @RhythmTool.UpperNoteData )

This note is like lower note but have an extra setting of being a physical note (see @RhythmTool.UpperNoteData.isPhysicalNote ).