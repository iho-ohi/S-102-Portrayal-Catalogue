# S-102 Portrayal Catalogue
<img src=./Images/figure-s102-pc-logo-white.svg alt="signal flags spelling S102" width=496 height=240>

S-102 GitHub repository for developing and maintaining S-102 Portrayal Catalogue

# issue tracking format
[i1]: https://github.com/iho-ohi/S-102-Portrayal-Catalogue/issues/1
[i3]: https://github.com/iho-ohi/S-102-Portrayal-Catalogue/issues/3
[i4]: https://github.com/iho-ohi/S-102-Portrayal-Catalogue/issues/4
[i7]: https://github.com/iho-ohi/S-102-Portrayal-Catalogue/issues/7
[i8]: https://github.com/iho-ohi/S-102-Portrayal-Catalogue/issues/8
[i9]: https://github.com/iho-ohi/S-102-Portrayal-Catalogue/issues/9
## Recent changes
Older changes are here: [Changelog.md](Changelog.md)

### 3.0.X - use with FC 3.0.X
* Misc changes
	* [#1][i1] Initial version 3.0.0 baseline to S-100 5.2 schemas, can be used with older FC data 2.1.X for testing
* Rule File / Symbol Updates
	* [#4][i4] Updated PC to match FC v3.0.0
	* [#7][i7] Tested FC with updated PC along with matching data from BSH (v3.0.0 data)
	* [#8][i8] Added NullInstruction rule placeholder for QualityOfBathymetryCoverage
	* [#8][i8] Rule QualityOfBathymetryCoverage XSLT element tag "NullInstruction" changed to "nullInstruction"
	* [#9][i9] Remove NauticalInformation processing, S-101 specific
 	* [#3][i3] Ensure mapping of depths to color values matches ENC
