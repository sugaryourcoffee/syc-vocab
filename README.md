sycvocab
========

`sycvocab` is a vocabulary trainer for the command line. `sycvocab` has a specific training cycle

1. Add words to `sycontact` as a first learning step. So you have to write the English word and then you are asked for the translation.
2. Train the words by typing the translation of the presented words. There are three categories of vocabularies. At the beginning all words are in category 3. Every time you provide the correct translation of a word it climbs up to the next better category. If you provide a wrong translation the word goes down one category. Words in lower categories are presented more often than words in higher categories.
3. A learning session is associated to a trainee so multiple users can learn on one PC and have their own learning statistics

Usage
=====

Get help on `sycvocab`

    $ sycvocab -h

Enter words to `sycvocab`

    $ sycvocab train englisch german

    Enter your name: pierre

    Enter done to end training session

    word? easy

    translation? leicht

    example sentence? To learn English is easy

    translation? Englisch zu lernen ist leicht

    done

    $


Learn words english german

    $ sycvocab learn

    Enter done to end learning session

    easy? leicht

    done

    $

Print statistics for all languages

    $ sycvocab statistics

    English
    153 words
    342 words learned
    102 words in category 1
    150 words in category 2
     90 words in category 3

    German
    153 words
    ...

Source
======

Contact
=======

<pierre@thesugars.de>
