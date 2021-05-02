# Introduction
Greetings. This is a Siberian Cyrillic-to-Latin conversion tool.

I have been working for the Sibirska Voljgota (Сибирска Вольгота) cultural group to promote the Siberian language (сибирской говор, *sibirskoj govor*) to the masses. The most of Siberian content is written in the Cyrillic script, with some letter changes depending on the orthography. My tool works mainly for the makovica orthography, so if you see -ЬО- in a Siberian text you want to transliterate, please change it to Cyrillic Ӧӧ beforehand, otherwise my tool will transliterate the digraph as -jo- and not -io-. 

There have also been several attempts to latinize Siberian ever since it was first introduced as a literary language in 2005. Different Siberian speakers have their own preferences in what letters or digraphs should be used instead of the Cyrillic ones. The discussions are mainly about transliteraring the 3 consonants that don't have one-to-one matches in Basic Latin, but there are in Extended Latin. Š Č Ž is the most perfect setpack to replace Ж Ч Ш not only in Siberian, but in any other Slavic language IMO, so this tool utilizes this variant ultimately.

## Usage
To use this tool, you don't have to download the file. You just need a browser to get to [this page](https://codepen.io/bignavigator/pen/YzNmyzw).

Now you can see a sample Article 1 of the Universal Declaration of Human Rights transliteration in Siberian. Put your own Siberian Cyrillic text into the first field, press on the «Transliterate» button, and get the Siberian Cyrillic text in the second field. Fairly easy, isn't it?

# Transliteration guide
Before asking questions like «Why does Letter X appear and not Letter Y?», please read this guide closely. Also keep in mind that this tool is developed for the makovica orthography.
## Consonants
The consonants are mostly standard for Latin-based Slavic languages. Ш Ч Ж are transliterated as Extended Latin Š Č Ž: they're also standard for most Latin-based Slavic languages.
* **б**орона → **b**orona
* **в**ӧдро → **v**iodro
* **г**анза → **g**anza
* **д**уран → **d**uran
* **ж**арница → **ž**arnica
* **з**агнӧт → **z**agniot
* малаха**й** → malaha**j**
* **к**ыска → **k**yska
* **л**юдь → **l**iudj
* **м**ыш → **m**yš
* **н**юня → **n**iunia
* **п**аря → **p**aria
* **р**анница → **r**annica
* **с**онечко → **s**onečko
* **т**янигуз → **t**ianiguz
* **ф**офан → **f**ofan
* **х**абарь → **h**abarj
* **ц**ерьква → **c**erjkva
* **ч**унарь → **č**unarj
* **ш**олоння → **š**olonnia

## Vowels
The vowels correspond to their Latin counterparts, Y replaces Ы as in Polish.
* **а**рава → **a**rava
* п**е**вник → p**e**vnik
* л**и**чнось → l**i**čnosj
* в**о**кно → v**o**kno
* в**у**лка → v**u**lka
* астрона**ў**т → astrona**w**t
* з**ы**к → z**y**k

### Iotated vowels
As you probably know, many Cyrillic languages include so-called iotated vowels: those're basically the /j/ plus a vowel sound, thus you can write one letter instead of two. Siberian has 5 such vowels. Depending on the position, they are transliterated either as J + vowel, or I + vowel. When they're located at the beginning of a word, after other vowels, or the hard/soft sign, they reflect the clear /j/ sound and are transliterated with J.
* **я**блок → **ja**blok
* **е**ван → **je**van
* **и**гра → **ji**gra
* **ӧ**рза → **jo**rza
* **ю**рмола → **ju**rmola

And when they're located after consonants, they simply patalize the consonants without adding the clear /j/ sound and are transliterated with I. Similar to Polish.
* т**я**тя → t**ia**tia
* т**ӧ**сӧл → t**io**siol
* т**ю**рючок → t**iu**riučok

This rule, however, doesn't apply for И and Е. That's because they don't have hard/non-iotated counterparts in Siberian (like Э in Russian). For example, while reading k**e**rpa (керпа), you need to assume it's pronounced like k**ie**rpa in Polish. As for И, there's simply no sense in writting two I's in a row. Some people may call it a soft analogue of Ы, however, Ы is actually a different phoneme.

### Hard and soft signs
The hard and the soft signs are both transliterated as J. When the soft sign appears at the end of a word, it patalizes the last consonant. In Siberian Latin, it's similar to Serbo-Croatian with the LJ and NJ digraphs (Љ and Њ in Cyrillic). However, there're many other consonants besides L and N that can be soft at the end of a word in Siberian. It would be too excessive to add a separate letter for each case as in West Slavic languages (ń, ť, ď, etc.). As such, the J replacing the soft sign will tell you to pronounce the consonant right before it softly.
* вя**зь** → via**zj**
* перве**нь** → perve**nj**
* в**ью**рок → v**ju**rok
* мыш**ъӧ** → myš**jo**
