# Immersion
ˌɪˈmərʒən ɪz dɪˈzaɪnd fər ˈtrænsˌletɪŋ əv ˈɛni ˈwɛbˌsaɪt frəm ˈɪŋlɪʃ tɪ IPA tɪ hɛlp wɪθ ˈlərnɪŋ ðə fəˈnɛtɪk ˈælfəˌbɛt // Immersion is designed for translating of any website from English to IPA to help with learning the phonetic alphabet

2018.05 - mitchellpkt@protonmail.com

Immersion application demo in GitHub root: `Immersion_Demo_NPR_Article.png`


## Quick translation how-to:
Video instructions: https://www.youtube.com/watch?v=T2IoYQgDoes

Text version:
-  Install FoxReplace
-  Go to the extension's options page
-  Click "Import from URL" and enter a link to the output file: 
`https://raw.githubusercontent.com/Mitchellpkt/Immersion/master/Outputs/IPA_only_top1e5.json`
- Click "Import and overwrite"
- To translate any webpage, go to English version and click "apply manual translations" through FoxReplace (or just enable "Apply automatic substitutions on page load")

---
## Comments

The code in this GitHUb is for generation of {English text} to {IPA symbols} dictionary.

The Jupyter notebook imports the dictionary specified by variable `DictStr`, then uses mphilli's `eng_to_ipa` to convert to IPA using the CMU database.

Part of a project for in-browser English-to-IPA conversion, for practicing IPA by written immersion... In the process, I added multi-OS support to eng_to_ipa, merged in here: https://github.com/mphilli/English-to-IPA/pull/4
