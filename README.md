# video2gif

> Convert Video (MP4/OGG/WEBM) to GIF.

You known that GIF is saved as Video on Twitter, I made this tool to convert those tiny videos to GIFs by using HTML Canvas. Due to performance issue this is not suited for any video that's longer than 10 seconds.

https://video2gif.egoist.sh

Example: https://video2gif.egoist.sh?video=https://video.twimg.com/tweet_video/D2aI3aFUkAE84AW.mp4 (Remote video doesn't work on FireFox because of CORS Policy)

![](assets/preview.png)

## Prior Art

[tweet2gif](https://github.com/idiotWu/tweet2gif/).

## Browser Support

Doesn't seem to work on Safari.

## License

MIT.

## Testing
#### Dev Environment Testing
| OperationSystem   | Chip         | Node     | npm     | npm registry                               | yarn     | yarn registry                              | Status |
|-------------------|--------------|----------|---------|--------------------------------------------|----------|--------------------------------------------|--------|
| MacOS Ventura13.1 | Apple M1 Pro | v20.10.0 | v10.2.3 | [TaoBao](https://registry.npm.taobao.org/) | v1.22.17 | [TaoBao](https://registry.npm.taobao.org/) | ✅      |

#### Video Type Testing
| VideoType | Status | 
|-----------|--------|
| MP4       | ✅      |
| MOV       | ❌      |
| OGG       | ✅      |
| WEBM      | ✅      |
