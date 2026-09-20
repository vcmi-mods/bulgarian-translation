The documentation for translation is [here](https://github.com/vcmi/vcmi/blob/develop/docs/translators/Translations.md).

Information for dubbing are [here](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)

Please create a new issue [here](https://github.com/vcmi-mods/bulgarian-translation/issues/new) for any mistake.

# How to play to Heroes of Might and Magic III in Bulgarian

1. Buy _Heroes of Might and Magic III Complete Edition_ on GOG (not the HD version)
1. Install the game
1. Download VCMI (free)
1. Install VCMI
1. When installing VCMI, specify the location of the base game's `Data`, `MP3`, and `Maps` folders.
1. Set the language to _Bulgarian_
1. Install the _Превод на български език_ mod
1. Launch the game

# Как да играете Heroes of Might and Magic III на български

1. Купете _Heroes of Might and Magic III Complete Edition_ от GOG (не HD версията)
1. Инсталирайте играта
1. Изтеглете VCMI (безплатно)
1. Инсталирайте VCMI
1. Когато инсталирате VCMI, посочете местоположението на папките `Data`, `MP3` и `Maps` на основната игра.
1. Задайте езика на _български_
1. Инсталирайте мода _Превод на български език_
1. Стартирайте играта

# How to dub

1. Copy a prolog/epilog from [`bulgarian-translation/content/config/vcmi-bulgarian/campaigns.json`](https://github.com/vcmi-mods/bulgarian-translation/tree/vcmi-1.7/content/config/vcmi-bulgarian)
2. Go to [Next-gen Kaldi: Text-to-speech](https://huggingface.co/spaces/csukuangfj/text-to-speech)
4. Paste the speech text
5. Select _Bulgarian_
6. Select a model (ex. supertonic)
4. Select a voice (ex. `3`)
7. Click on _Generate_
8. Download the audio file
9. Retrieve the property for the speech in the [`bulgarian-translation/content/config/vcmi-bulgarian/campaigns.json`](https://github.com/vcmi-mods/bulgarian-translation/tree/vcmi-1.7/content/config/vcmi-bulgarian) file
10. Retrieve the related audio filename in the [empty-translation mod](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)
11. Rename the audio file
12. Move the file to `bulgarian-translation/content/sounds/` folder

# How to contribute

1. Go to the GitHub mod page: https://github.com/vcmi-mods/bulgarian-translation
2. Fork the repository by clicking on the "Fork" button
3. Browse to the file you want to change
4. Click on the pencil button to edit the file
5. Edit the file
6. Click on the "Commit changes..." button
7. Click on the "Pull request" tab
8. Click on the "Create Pull Request" button
9. Write a description and create the PR (Pull Request)