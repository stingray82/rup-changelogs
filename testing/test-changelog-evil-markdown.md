## 3.0.0 - 20 April 2026
### New
- Clean baseline entry for comparison
### Fixed
- Standard fixed entry
### Tweaked
- Standard tweaked entry

## 3.0.0-alpha - 19 April 2026
### New
- Extra prerelease markdown header should parse
### Update
- Singular Update heading should normalize correctly
### warning
- Lowercase heading should still normalize

## 3.0.0-beta.1 (18 April 2026)
### New
- Parenthesized date format test
### Improvement
- Very very very long markdown bullet entry intended to test wrapping behaviour inside the timeline and cards layouts without custom CSS
### Known Issue
- VeryLongSingleWordEntryThatMayNeedOverflowHandlingInCustomThemesOrBuilders

## 3.0.0-rc1 - 17 April 2026
### Fixed
- Release candidate parsing test
### Experimental
- Experimental heading should still parse
### Deprecated
- Deprecated heading should still parse

## Version 3.0.0-dev - 16 April 2026
### New
- Version keyword heading should parse if supported

### Compatibility
- Compatibility label test

### Security
- Security label test

## 3.0.0-preview 15 April 2026
### New
- Plain markdown version and date without dash may or may not parse depending on regex
### Changed
- Changed alias should normalize
### Removed
- Removed alias should normalize

## v3.0.0-canary.2 - 14 April 2026
### Experimental
- Canary build test
### Performance
- Performance heading should render correctly
### Info
- Explicit info entry should use fallback label styling

## 3.0.0-nightly+build.7 - 13 April 2026
### New
- Build metadata parsing test
### Known Issue
- Build metadata should not break visible version output

## 3.0.0-pre - 12 April 2026
### new
- Lowercase type heading should normalize
### fixed
- Lowercase fixed heading should normalize
### updated
- Lowercase updated heading should normalize

## 2.9.9 - 11 April 2026
### BUG
- Unknown uppercase heading should fall back
### Feature
- Unknown heading should fall back
### Notice
- Unknown heading should fall back

## 2.9.8 - 10 April 2026
### New
- Entry with colon: extra colon content should remain in text: yes it should
### Tweaked
- Entry with commas, semicolons; and punctuation! should still parse

## 2.9.7 - 09 April 2026
### New
- Entry with normal bullet
- Second bullet under same heading
- Third bullet under same heading

## 2.9.6 - 08 April 2026
### SeCuRiTy
- Mixed case type heading should normalize if alias exists
### WaRnInG
- Mixed case warning heading should normalize too

## 2.9.5 - 07 April 2026
### Experimental
- Unicode test – en dash, emoji ✅, accented text café, naïve, résumé
### Tweaked
- Symbols test #hashtag @mention /path/to/file ?query=yes&ok=true

## 2.9.4 - 06 April 2026
### New
- Short line

This paragraph should be ignored because it is not a bullet item.

### Fixed
- Another valid entry after an invalid paragraph

## 2.9.3 - 05 April 2026
### New
### Fixed
- Missing bullet under New above should not break later sections
### Improvement
- Valid improvement entry after malformed one

## 2.9.2 - 04 April 2026
### New
- Leading and trailing spaces should be trimmed      
### Updated
- Another valid line      

## 2.9.1 - 03 April 2026
### Compatibility
- Theme compatibility wording
### Breaking
- Breaking label support test
### Hotfix
- Hotfix label support test

## 2.9.0 - 02 April 2026
### New
- Duplicate type one
- Duplicate type two
- Duplicate type three
### Fixed
- Duplicate type four

## 2.8.9 - 01 April 2026
### Warn
- Alias warn should normalize to Warning
### Improve
- Alias improve should normalize to Improvement
### Tweak
- Alias tweak should normalize to Tweaked

## 2.8.8 - 31 March 2026
### Added
- Added alias support check
### Change
- Change alias support check
### Remove
- Remove alias support check

## 2.8.7 - 30 March 2026
### New
- Mixed historic markdown support check
### Update
- Another update entry

## 2.8.6 (29 March 2026)
### New
- Parenthesized markdown date compatibility check

## 2.8.5 - 28 March 2026
### Experimental
### Fixed
- Empty experimental section above should not break later one

## invalid heading
### New
- This block should ideally not become a valid release

## 2.8.4 - 27 March 2026
### New
- Valid section after invalid heading should still recover parser state

## 2.8.3
### New
- Version without date should still parse if supported
### Fixed
- Another entry without date

## Version 2.8.2
### New
- Word version heading without date if supported

## 2.8.1 - 26 March 2026
### New
- Final sanity check entry
