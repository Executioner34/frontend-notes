Модель DOM HTML5 имеет методы, свойства и события для элементов `<audio>` и `<video>`

## Аудио/видео методы HTML

Method | Description
------ | ---------
[addTextTrack()](https://www.w3schools.com/tags/av_met_addtexttrack.asp) [Russian](https://andew.ru/pages/page/html5-audio-video-js-addtexttrack.php)|Adds a new text track to the audio/video
[canPlayType()](https://www.w3schools.com/tags/av_met_canplaytype.asp) [Russian](https://andew.ru/pages/page/html5-audio-video-js-canplaytype.php)|Checks if the browser can play the specified audio/video type
[load()](https://www.w3schools.com/tags/av_met_load.asp) [Russian](https://andew.ru/pages/page/html5-audio-video-js-load.php)|Re-loads the audio/video element
[play()](https://www.w3schools.com/tags/av_met_play.asp) [Russian](https://html5css.ru/tags/av_met_play.php)|Starts playing the audio/video
[pause()](https://www.w3schools.com/tags/av_met_pause.asp) [Russian](https://html5css.ru/tags/av_met_pause.php)|Pauses the currently playing audio/video

---

## HTML аудио/видео свойства. [Русский вариант](https://html5css.ru/tags/ref_av_dom.php)

Property | Description
------------- | ---------------
[audioTracks](https://www.w3schools.com/tags/av_prop_audiotracks.asp)|Returns an AudioTrackList object representing available audio tracks
[autoplay](https://www.w3schools.com/tags/av_prop_autoplay.asp)|Sets or returns whether the audio/video should start playing as soon as it is loaded
[buffered](https://www.w3schools.com/tags/av_prop_buffered.asp)|Returns a TimeRanges object representing the buffered parts of the audio/video
[controller](https://www.w3schools.com/tags/av_prop_controller.asp)|Returns the MediaController object representing the current media controller of the audio/video
[controls](https://www.w3schools.com/tags/av_prop_controls.asp)|Sets or returns whether the audio/video should display controls (like play/pause etc.)
crossOrigin | Sets or returns the CORS settings of the audio/video
[currentSrc](https://www.w3schools.com/tags/av_prop_currentsrc.asp)|Returns the URL of the current audio/video
[currentTime](https://www.w3schools.com/tags/av_prop_currenttime.asp)|Sets or returns the current playback position in the audio/video (in seconds)
[defaultMuted](https://www.w3schools.com/tags/av_prop_defaultmuted.asp)|Sets or returns whether the audio/video should be muted by default
[defaultPlaybackRate](https://www.w3schools.com/tags/av_prop_defaultplaybackrate.asp)|Sets or returns the default speed of the audio/video playback
[duration](https://www.w3schools.com/tags/av_prop_duration.asp)|Returns the length of the current audio/video (in seconds)
[ended](https://www.w3schools.com/tags/av_prop_ended.asp)|Returns whether the playback of the audio/video has ended or not
[error](https://www.w3schools.com/tags/av_prop_error.asp)|Returns a MediaError object representing the error state of the audio/video
[loop](https://www.w3schools.com/tags/av_prop_loop.asp)|Sets or returns whether the audio/video should start over again when finished
[mediaGroup](https://www.w3schools.com/tags/av_prop_mediagroup.asp)|Sets or returns the group the audio/video belongs to (used to link multiple audio/video elements)
[muted](https://www.w3schools.com/tags/av_prop_muted.asp)|Sets or returns whether the audio/video is muted or not
[networkState](https://www.w3schools.com/tags/av_prop_networkstate.asp)|Returns the current network state of the audio/video
[paused](https://www.w3schools.com/tags/av_prop_paused.asp)|Returns whether the audio/video is paused or not
[playbackRate](https://www.w3schools.com/tags/av_prop_playbackrate.asp)|Sets or returns the speed of the audio/video playback
[played](https://www.w3schools.com/tags/av_prop_played.asp)|Returns a TimeRanges object representing the played parts of the audio/video
[preload](https://www.w3schools.com/tags/av_prop_preload.asp)|Sets or returns whether the audio/video should be loaded when the page loads
[readyState](https://www.w3schools.com/tags/av_prop_readystate.asp)|Returns the current ready state of the audio/video
[seekable](https://www.w3schools.com/tags/av_prop_seekable.asp)|Returns a TimeRanges object representing the seekable parts of the audio/video
[seeking](https://www.w3schools.com/tags/av_prop_seeking.asp)|Returns whether the user is currently seeking in the audio/video
[src](https://www.w3schools.com/tags/av_prop_src.asp)|Sets or returns the current source of the audio/video element
[startDate](https://www.w3schools.com/tags/av_prop_startdate.asp)|Returns a Date object representing the current time offset
[textTracks](https://www.w3schools.com/tags/av_prop_texttracks.asp)|Returns a TextTrackList object representing the available text tracks
[videoTracks](https://www.w3schools.com/tags/av_prop_videotracks.asp)|Returns a VideoTrackList object representing the available video tracks
[volume](https://www.w3schools.com/tags/av_prop_volume.asp)|Sets or returns the volume of the audio/video

---

## HTML-аудио/видео события. [Русский вариант](https://html5css.ru/tags/ref_av_dom.php)

Event | Description
-------- | ---------
[abort](https://www.w3schools.com/tags/av_event_abort.asp)|Fires when the loading of an audio/video is aborted
[canplay](https://www.w3schools.com/tags/av_event_canplay.asp)|Fires when the browser can start playing the audio/video
[canplaythrough](https://www.w3schools.com/tags/av_event_canplaythrough.asp)|Fires when the browser can play through the audio/video without stopping for buffering
[durationchange](https://www.w3schools.com/tags/av_event_durationchange.asp)|Fires when the duration of the audio/video is changed
emptied|Fires when the current playlist is empty
[ended](https://www.w3schools.com/tags/av_event_ended.asp)|Fires when the current playlist is ended
[error](https://www.w3schools.com/tags/av_event_error.asp)|Fires when an error occurred during the loading of an audio/video
[loadeddata](https://www.w3schools.com/tags/av_event_loadeddata.asp)|Fires when the browser has loaded the current frame of the audio/video
[loadedmetadata](https://www.w3schools.com/tags/av_event_loadedmetadata.asp)|Fires when the browser has loaded meta data for the audio/video
[loadstart](https://www.w3schools.com/tags/av_event_loadstart.asp)|Fires when the browser starts looking for the audio/video
[pause](https://www.w3schools.com/tags/av_event_pause.asp)|Fires when the audio/video has been paused
[play](https://www.w3schools.com/tags/av_event_play.asp)|Fires when the audio/video has been started or is no longer paused
[playing](https://www.w3schools.com/tags/av_event_playing.asp)|Fires when the audio/video is playing after having been paused or stopped for buffering
[progress](https://www.w3schools.com/tags/av_event_progress.asp)|Fires when the browser is downloading the audio/video
[ratechange](https://www.w3schools.com/tags/av_event_ratechange.asp)|Fires when the playing speed of the audio/video is changed
[seeked](https://www.w3schools.com/tags/av_event_seeked.asp)|Fires when the user is finished moving/skipping to a new position in the audio/video
[seeking](https://www.w3schools.com/tags/av_event_seeking.asp)|Fires when the user starts moving/skipping to a new position in the audio/video
[stalled](https://www.w3schools.com/tags/av_event_stalled.asp)|Fires when the browser is trying to get media data, but data is not available
[suspend](https://www.w3schools.com/tags/av_event_suspend.asp)|Fires when the browser is intentionally not getting media data
[timeupdate](https://www.w3schools.com/tags/av_event_timeupdate.asp)|Fires when the current playback position has changed
[volumechange](https://www.w3schools.com/tags/av_event_volumechange.asp)|Fires when the volume has been changed
[waiting](https://www.w3schools.com/tags/av_event_waiting.asp)|Fires when the video stops because it needs to buffer the next frame

---

## Пример

[Ссылка](https://andew.ru/pages/page/html5-audio-video-js-media-demonstration.php)