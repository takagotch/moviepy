### moviepy
---
https://github.com/Zulko/moviepy/

http://zulko.github.io/moviepy/

```py
// audio/fx/audio_loop.py

from ..AudioClip import concatenate_audioclips

def audio_loop(audioclip, nloops=None, duration=None):
  """
  """
  if duration is not None:
    
     nloops = int( duration/ audioclip.duration)+1
     return concatenate_audioclips(nloops*[audioclip]).set_duration(duration)
     
   else:
   
     return concatenate_audioclips(nloop*[audioclip])

```

```
```

```
```

