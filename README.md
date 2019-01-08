# Resource Hints

## Spec
https://www.w3.org/TR/resource-hints/

## Test Result
| case         | url                                              | webpagetest           | waterfall                                                                                                             |
|--------------|--------------------------------------------------|-----------------------|-----------------------------------------------------------------------------------------------------------------------|
| normal       | https://poohding.github.io/wpo/normal.html       | http://bit.ly/2CWcMdB | ![normal](https://user-images.githubusercontent.com/22700874/50769326-f1bc8800-12c6-11e9-9714-83d907f5fa0e.png)       |
| dns-prefetch | https://poohding.github.io/wpo/dns-prefetch.html | http://bit.ly/2CUFLOU | ![dns-prefetch](https://user-images.githubusercontent.com/22700874/50769352-0e58c000-12c7-11e9-970e-b5b84ca6f904.png) |
| preconnect   | https://poohding.github.io/wpo/preconnect.html   | http://bit.ly/2CV8gMg | ![preconnect](https://user-images.githubusercontent.com/22700874/50769358-1153b080-12c7-11e9-8df1-3fa279bddc73.png)   |

## 참고문서
- https://css-tricks.com/prefetching-preloading-prebrowsing/
- https://medium.com/@pakss328/resource-hint-8fb4e56ee042
