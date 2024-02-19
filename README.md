## Intramarket-Differencing
### Strategy Goals
1) Identify Highly correlated crypto pairs. Could be useful to create a heatmap of a large sample of tokens we find interesting, then choose promising pairs from the map. Heatmap could be used in our presentation.
2) Identify indicators for comparing correlated pairs in order to find divergences.
3) Identify the threshold for our stationary indicator in order to enter long/short positons on each asset.
4) This strategy is relatively delta neutural as we are trading between pairs so our position is somewhat "hedged", so it will likely be useful to incorporate leverage in order to amplify returns (Adding leverage simply increases the standard devation of returns, thereby artificallly increasing volatility).
5) Could be useful to see if more volatile tokens reduce our need for leverage in certian cases.
6) Risk managment will lilely be monitoring the cross-asset correlation, and liquidating the positon if the cross-asset relationship has deteriated significantly/below our threshold.
