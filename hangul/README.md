# Raven Hangul
## Design
### Goals
1. As fast as possible for most users.
2. Try to be intuitive to non-native users, to reduce learning cost as much as possible.

### Principles
1. Reduce the keys required overall.
2. Match the vowels with their frequency.
3. Provide dedicated keys for common composite trailing consonants.

## Keymap
The `×` (blank) keys either indicate blank input or act as stream breakers.

### First stage
Keys are positioned to try reflecting their mapped Hangul's pronunciation.

Entering blank keys in this stage will terminate the input flow after the second key is pressed, as long as they are not blank keys, useful for typing bare vowels.

| Q | W | E | R | T | Y | U | I | O | P |
| - | - | - | - | - | - | - | - | - | - |
| ㆆ | × | ㄸ | ㄹ | ㅌ | ㅇ | ㅉ | × | × | ㅍ |
| ㅆ | ㅅ | ㄷ | ㄲ | ㄱ | ㅎ | ㅈ | ㅋ | ㆁ |
|   | ㅿ | ㆅ | ㅊ | ㅃ | ㅂ | ㄴ | ㅁ |

### Second stage
Keys are positioned to try reflecting the frequency of each mapped vowel.

If a non-blank key is entered in the first stage, entering blank keys in this stage will terminate the input flow immediately, useful for typing bare consonants.

| Q | W | E | R | T | Y | U | I | O | P |
| - | - | - | - | - | - | - | - | - | - |
| × | ㅒ | ㅘ | ㅛ | ㅝ | ㅠ | ㅟ | ㅔ | ㅞ | × |
| × | ㅕ | ㅏ | ㅓ | ㅜ | ㅐ | ㅗ | ㅣ | ㅡ |
|   | × | × | ㅚ | ㅑ | ㅖ | ㅙ | ㅢ |

### Third stage
Keys are positioned to try reflecting their mapped Hangul's pronunciation.

Entering blank keys in this stage will terminate the input flow immediately.

| Q | W | E | R | T | Y | U | I | O | P |
| - | - | - | - | - | - | - | - | - | - |
| ㄽ | ㄻ | × | ㄺ | ㅌ | ㅇ | ㄶ | ㅄ | ㅀ | ㅍ |
| ㅆ | ㅅ | ㄷ | ㄲ | ㄱ | ㅎ | ㅈ | ㅋ | ㄹ |
|  | ㄳ | ㄵ | ㅊ | ㄼ | ㅂ | ㄴ | ㅁ |