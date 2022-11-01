# ComposePager

## Preview

<div align=center><img src="../img/compose_pager.gif" width=25%></div>

## Usage


```kotlin
/**
 * Equivalent to the ViewPager in android
 * @param pageCount Sum page count
 * @param modifier
 * @param composePagerState ComposePager's state
 * @param orientation Scroll orientation
 * @param userEnable Whether the user can scroll
 * @param pageCache The number of pagers cached on the left and right sides
 * @param scrollableInteractionSource Scroll state monitor
 * @param content Content of compose
 */
@Composable
fun ComposePager()
```