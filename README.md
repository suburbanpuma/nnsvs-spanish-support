### NOTICE
By using all OR ANY PART of this project you MUST the DYVAUX license at https://github.com/DYVAUX/nnsvs-english-support/blob/main/LICENSE.md

This includes using parts of DYVAUX's work in yours. If you have questions about the license please contact DYVAUX.

I (subpum) put this in here because even if it's my repository it's still DYVAUX's legal assets. Respect their work.
___

## Other:

| Phoneme | X-SAMPA | Description               |
| ------- | ------- | --------------------------|
| br      |         | Deprecated (Inhale)       |
| exh     |         | Exhale                    |
| axh     |         | Voiced Exhale             |
| pau     |         | Silence                   |
| q       | ?       | Glottal Stop              |
| cl      | :       | Closure (Held Consonants) |
| vf      |         | Vocal Fry                 |
| trash   |         | Junk Phoneme              | 

## Vowels:

| Phoneme | X-SAMPA | Explaination                    | Example                                 |
| ------- | ------- | ------------------------------- | --------------------------------------- |
| a       | a       | central open unrounded vowel    | <ins><b>A</ins></b>n<ins><b>a</ins></b> |
| e       | e       | close-mid front unrounded vowel | <ins><b>E</ins></b>va                   |
| i       | i       | close front unrounded vowel     | L<ins><b>i</ins></b>nda                 |
| o       | o       | close-mid back rounded vowel    | T<ins><b>o</ins></b>pe                  |
| u       | u       | close back rounded vowel        | <ins><b>U</ins></b>no                   |

## Semi-Vowels:
(Semi-vowels function as consonants and perform "diphthong-like" tasks.)
| Phoneme | X-SAMPA | Explaination                    | Example                                 |
|---------|---------|---------------------------------|-----------------------------------------|
| j       | j       | palatal approximant      | A<ins><b>i</ins></b>re (a <ins><b>y</ins></b> r e), t<ins><b>i</ins></b>erra (t <ins><b>y</ins></b> e rr a), sa<ins><b>y</ins></b>o (s a <ins><b>y</ins></b> o) |
| w       | w       | labial-velar approximant | Pa<ins><b>u</ins></b>sa (p a <ins><b>w</ins></b> s a), f<ins><b>u</ins></b>ego (f <ins><b>w</ins></b> e gh o)                                                   |

## Consonants:

| Phoneme | X-SAMPA | Explanation                        | Example                   |
|---------|---------|------------------------------------|---------------------------|
| b       | b       | voiced bilabial plosive            | <ins><b>b</ins></b>año (<ins><b>b</ins></b> a ny o)           |
| bh      | B       | voiced bilabial fricative          | a<ins><b>b</ins></b>aco (a <ins><b>bh</ins></b> a k o)        |
| ch      | tS      | voiceless postalveolar affricate   | <ins><b>ch</ins></b>oripan (<ins><b>ch</ins></b> o r i p a n) |
| d       | d       | voiced alveolar plosive            | <ins><b>d</ins></b>ía (<ins><b>d</ins></b> i a)               |
| dh      | D       | voiced dental fricative            | an<ins><b>d</ins></b>ina (a n <ins><b>dh</ins></b> i n a)     |
| f       | f       | voiceless labiodental fricative    | <ins><b>f</ins></b>arol (<ins><b>f</ins></b> a r o l)         |
| g       | g       | voiced velar plosive               | <ins><b>ga</ins></b>to (<ins><b>g</ins></b> a t o)            |
| gh      | G       | voiced velar fricative             | a<ins><b>g</ins></b>ua (a <ins><b>gh</ins></b> w a)           |
| k       | k       | voiceless velar plosive            | <ins><b>c</ins></b>asa (<ins><b>k</ins></b> a s a)            |
| l       | l       | lateral alveolar approximant       | <ins><b>l</ins></b>ame (<ins><b>l</ins></b> a m e)            |
| ll      | L       | voiced palatal lateral approximant | po<ins><b>ll</ins></b>o (p o <ins><b>ll</ins></b> o)          |
| m       | m       | bilabial nasal                     | <ins><b>m</ins></b>adre (<ins><b>m</ins></b> a dh r e)         |
| n       | n       | alveolar nasal                     | <ins><b>n</ins></b>adie (<ins><b>n</ins></b> a dh j e)         |
| ny      | J       | palatal nasal                      | <ins><b>ñ</ins></b>oquis (<ins><b>ny</ins></b> o k i s)       |
| p       | p       | voiceless bilabial plosive         | <ins><b>p</ins></b>uerta (<ins><b>p</ins></b> w e r t a)      |
| r       | 4       | alveolar flap                      | la<ins><b>r</ins></b>ga (l a <ins><b>r</ins></b> gh a)         |
| rr      | r       | alveolar trill                     | <ins><b>r</ins></b>ara (<ins><b>rr</ins></b> a r a)           |
| s       | s       | voiceless alveolar fricative       | <ins><b>s</ins></b>uena (<ins><b>s</ins></b> w e n a)         |
| sh      | S       | voiceless postalveolar fricative   | <ins><b>sh</ins></b>ow (<ins><b>sh</ins></b> o w)             |
| t       | t       | voiceless alveolar plosive         | <ins><b>t</ins></b>ema (<ins><b>t</ins></b> e m a)            |
| x       | x       | voiceless velar fricative          | <ins><b>j</ins></b>amón (<ins><b>x</ins></b> a m o n)         |
| y       | j\      | voiced palatal fricative           | <ins><b>y</ins></b>ace (<ins><b>y</ins></b> a s e)            |
| z       | T       | voiced alveolar fricative          | <ins><b>z</ins></b>eta (<ins><b>z</ins></b> e t a)            |


## Dialect and Reference Allophones:
These phonemes are here for reference and proper support. Most of these can be handled contextually, and you <ins><b>shouldn't</ins></b> use them.
Not that they will blow up your model, but to save VRAM.

| Phoneme | X-SAMPA | Explanation                           | Example               | Dialect                                               |
|---------|---------|---------------------------------------|-----------------------|-------------------------------------------------------|
| ts      | ts      | voiceless alveolar sibilant affricate | <ins><b>ch</ins></b>ala (<ins><b>ts</ins></b> a l a)      | Reference allophone for ch.                           |
| zh      | Z       | voiced postalveolar fricative         | e<ins><b>ll</ins></b>os (e <ins><b>zh</ins></b> o s)                     | Reference allophone for ll.                           |
| sh      | S       | voiceless postalveolar fricative      | <ins><b>ch</ins></b>ala (<ins><b>sh</ins></b> a l a) e<ins><b>ll</ins></b>os (e <ins><b>sh</ins></b> o s)      | Reference allophone for ll/ch.                        |
| h       | h       | voiceless glottal fricative           | obi<ins><b>s</ins></b>po (o bv i <ins><b>h</ins></b> p o) | Reference allophone for s/x.                          |
| v       | v       | voiced labiodental fricative          | a<ins><b>f</ins></b>gano (a <ins><b>v</ins></b> gh a n o) | Reference allophone for f (before voiced consonants). |
| dj      | J\        | voiced palatal plosive                                      | <ins><b>gu</ins></b>ía (<ins><b>dj</ins></b> i a)                     | Reference allophone for g (before some vowels).       |
| ng      | N       | velar nasal                           | di<ins><b>n</ins></b>go (d i <ins><b>ng</ins></b> g o)    | Reference allophone for n (before velar consonants).  |


Notes:
* `sh` and `zh` are sometimes used as allophones for `ll`. You should still label them as `ll` for dictionary compatiblity. However, these phonmemes are useful for foreign words.
  
* Some speakers enounter "yeísmo", or the merging of "ll" and "y". These speakers can label "ll" as `y` instead to slightly reduce the amount of training data needed.
  
* Some speakers merge the hard and soft "b/d/g" sounds. These speakers can label all "b/d/g" as [`b`/`d`/`g`] and ignore the [`bh`/`dh`/`gh`] phonemes. Speakers without this merger can also drop [`bh`/`dh`/`gh`] to simplify the dataset, which will cause most "b/d/g” instances to sound softer (due to more instances of the soft sound in the samples). Doing so also creates a slight risk that the model may use a hard "b/d/g" at an incorrect time.
  
* Older Romance HED-based banks might use the `y` phoneme as both a consonant AND semivowel. This is due to VRAM saving measures, and is not encouraged with this release, as they're different phonemes. Do not worry if your old data is labeled that way though, as it's still supported.
  
* `x` covers all "h/soft J/aspirated s" sounds contextually. So only one phoneme is required. For speakers who want to differentiate, the `h` phoneme could be used along with the others. Note that this will increase the amount of data required and won't be supported in the dictionary.

* `f` is used for both devoiced "f" and voiced "v" sounds.

* Some Chilean speakers say `ts` instead of `ch`.

* Some Chilean speakers say `sh` instead of `ch`.

* In most cases you should still label these as `ch` for dictionary compatiblity. Only differenciate if the speaker wants to support them both (optional).
