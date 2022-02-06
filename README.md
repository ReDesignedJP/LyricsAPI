# LyricsAPI
> Currently only docs are provided.


## BASE URL
```https://lyrics-api.staycute.xyz/api/test/{provider}/{song name}```

### SUPPORTED LYRICS PROVIDERS
Spotify  
Genius

### Query Parameters
timing (default false) -> provides ms unit of time synchronized with the lyrics.

> Only Spotify Provider, not Genius

### Example Request Url
Genius
  - [https://lyrics-api.staycute.xyz/api/test/genius/Revolver Honeycomebear](https://lyrics-api.staycute.xyz/api/test/genius/Revolver%20Honeycomebear)
  
Spotify
  - Without Timing Data [https://lyrics-api.staycute.xyz/api/test/spotify/RevolverHoneycomebear](https://lyrics-api.staycute.xyz/api/test/spotify/Revolver%20Honeycomebear)
  - With Timing Data [https://lyrics-api.staycute.xyz/api/test/spotify/RevolverHoneycomebear?timing=true](https://lyrics-api.staycute.xyz/api/test/spotify/Revolver%20Honeycomebear?timing=true)
  
