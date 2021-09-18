![Header](/.github/readme/fmn_header.png)

<h1 align="center">SmartQuiz</h1>

<p align="center">  
SmartQuiz is an Android app for memorizing information via flashcards. Simplicity, usability, speed were taken into account in the process of developing this educational program. This app provides excellent conditions for achieving high efficiency of memorization.
</p>


Features
--------

<img src="/.github/readme/preview.gif" align="right" width="32%"/>

* Import/export of files.
* Support of CSV, Tab text or any other kind of Delimiter-Separated Values.
* Intervals ([Spaced repetition](https://en.wikipedia.org/wiki/Spaced_repetition)). You can specified your own interval scheme for each deck.
* Several testing methods. There are 'Self testing', 'Testing with variants', 'Spell check'.
* Pronunciation of the text via TTS. You can choose languages for questions and answers, autospeaking of them.
* Hiding the text of a question to stimulate improvement of listening skills that is very useful in foreign language learning.
* Card inversion.
* Hints in the form of masking letters.
* 'Motivational timer' that will make you concentrate on your studies (optionally).
* Saving settings of deck as presets and reusing them in order to avoid routine work on settings.
* Editing and searching cards right in the exercise.
* 'Walking mode' that enables you do the exercise without looking at the screen.
* 'Autoplaying mode'. In this mode questions and answers are pronounced sequentially. You can combine your own activities and repetition of teaching material.
* Catalog of pre-made decks. The catalog contains many decks for language learning, which includes basic sets of words, thematic words and phrases, whole sentences.
* Grouping decks into separate lists
* Customizing the card appearance
* Dark theme


Architecture
------------

See the dedicated page [here](/.github/readme/ARCHITECTURE.md).

Libraries Used
--------------

* [kotlinx-coroutines](https://github.com/Kotlin/kotlinx.coroutines)
* [kotlinx-serialization](https://github.com/Kotlin/kotlinx.serialization)
* [androidx.appcompat](https://developer.android.com/jetpack/androidx/releases/appcompat)
* [androidx.fragment](https://developer.android.com/jetpack/androidx/releases/fragment)
* [androidx.constraintlayout](https://developer.android.com/jetpack/androidx/releases/constraintlayout)
* [androidx.navigation](https://developer.android.com/jetpack/androidx/releases/navigation)
* [androidx.viewpager2](https://developer.android.com/jetpack/androidx/releases/viewpager2)
* [material-components](https://github.com/material-components/material-components-android)
* [leakcanary](https://github.com/square/leakcanary)
* [sqldelight](https://github.com/cashapp/sqldelight)
* [klock](https://github.com/korlibs/klock)
* [materialrangebar](https://github.com/oli107/material-range-bar)
* [Brackeys-IDE](https://github.com/massivemadness/Brackeys-IDE)
* [Apache Commons CSV](https://commons.apache.org/proper/commons-csv/)

License
-------

[GNU General Public License v3.0](LICENSE)

