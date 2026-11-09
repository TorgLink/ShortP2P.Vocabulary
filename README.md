# ShortP2P.Vocabulary

Vocabulary zip packs for ShortP2P dictionary short-text compression ([SMT-3](https://botticelli.youtrack.cloud/issue/SMT-3)).

## Packs (v1)

| File | Language | Source list |
|------|----------|-------------|
| `RU_vocabulary_v1.zip` | Russian | `ru_50k.txt` |
| `EN_vocabulary_v1.zip` | English | `en_50k.txt` |
| `FR_vocabulary_v1.zip` | French | `fr_50k.txt` |
| `DE_vocabulary_v1.zip` | German | `de_50k.txt` |
| `ES_vocabulary_v1.zip` | Spanish | `es_50k.txt` |

Each pack takes the top 3000 lowercase tokens from FrequencyWords 2016.

## Pack format
- File name: `<Lang>_vocabulary_v<version>.zip`
- `tokens.txt`: lowercase TSV lines `<index>\t<word>`
- `ReadMe.txt`: English attribution for FrequencyWords (CC BY-SA 4.0)

## Source
Word lists derived from [hermitdave/FrequencyWords](https://github.com/hermitdave/FrequencyWords).
License: Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)
Thanks to: Hermit Dave

## Branch
`dev/0.2` — packs aligned with ShortP2P 0.2 line.
