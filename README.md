# proof-dictionary

This dictionary is for [proofdict](https://github.com/proofdict/proofdict).

- Dictionary: <https://hata6502.github.io/proof-dictionary>
- Editor: <https://hata6502.github.io/proof-dictionary/editor>
- JSON API: <https://hata6502.github.io/proof-dictionary/dictionary.json>

## Usage

### Add dictionary

If you want to add new rule to your dictionary, you can add new rule by following steps: 

Visit your [editor page](https://hata6502.github.io/proof-dictionary/editor):

- <https://hata6502.github.io/proof-dictionary/editor>

### Update dictionary

If you want to update the rule from your dictionary, you can edit it by following steps: 

1. Visit [_data/proofdict][]
2. Select the file for updating
3. Edit the file by click ![Edit this file](docs/assets/pencil.png) icon

### Remove dictionary

If you want to remove unnecessary rule from your dictionary, you can remove it by following steps: 

1. Visit [_data/proofdict][]
2. Select the file for removing
3. Remove the file by click ![Delete this file](docs/assets/trashcan.png) icon

### Test dictionary

You can check your proof-dictionary is valid format.

Run following command in your local:

    npm install
    npm test

[_data/proofdict]: _data/proofdict "dictionary data directory"
