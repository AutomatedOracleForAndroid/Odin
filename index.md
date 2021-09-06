## Odin: Detecting Non-crashing Functional Bugs in Android Apps via Deep-State Differential Analysis


### Tools in evaluation

- Odin (Binary):

	* [https://github.com/AutomatedOracleForAndroid/Barbara/raw/gh-pages/Barbara-bin.rar](https://github.com/AutomatedOracleForAndroid/Barbara/raw/gh-pages/Barbara-bin.rar)

- Monkey: Shipped with all Android deivce

- APE: [APE](http://gutianxiao.com/ape/)

- ComboDroid: [ComboDroid](https://github.com/the-themis-benchmarks/combodroid)

- Genie: [Genie](https://github.com/tingsu)

### Subjects

- Additional 11 subjects: [subjects-new](https://1drv.ms/u/s!Ap89R8sDM76GpPcXtXgMl5d-btW22w?e=N3pHeu)

- Subjects used by Genie: [subjects-comparsion](https://1drv.ms/u/s!Ap89R8sDM76GpPcWN9RcFMWcTw-Skw?e=frcdsD)

### Execution logs and results

- [logNResults] (https://1drv.ms/u/s!Ap89R8sDM76GpPcWN9RcFMWcTw-Skw?e=frcdsD)

### Bug Lists

- Additional 11 subjects:

	* AntennaPod: [4991](https://github.com/AntennaPod/AntennaPod/issues/4991
), [4953](https://github.com/AntennaPod/AntennaPod/issues/4953
), [5045](https://github.com/AntennaPod/AntennaPod/issues/5045
), [4279](https://github.com/AntennaPod/AntennaPod/issues/4279
), [4275](https://github.com/AntennaPod/AntennaPod/issues/4275
), [4123](https://github.com/AntennaPod/AntennaPod/issues/4123
)

	* AnkiDroid: [9805](https://github.com/ankidroid/Anki-Android/issues/9085
)

	* AmazeFileManager: [2531](https://github.com/TeamAmaze/AmazeFileManager/issues/2531), [2620](https://github.com/TeamAmaze/AmazeFileManager/issues/2620)

	* And-bible: [1482](https://github.com/AndBible/and-bible/issues/1482
), [1432](https://github.com/AndBible/and-bible/issues/1432
)

	* AnyMemo: [512](https://github.com/helloworld1/AnyMemo/issues/512
)

	* Makor: [1366](https://github.com/gsantner/markor/issues/1366
)

	* Materialistic: [1451](https://github.com/hidroh/materialistic/issues/1451)

	* Transistor: [360](https://github.com/y20k/transistor/issues/360
), [361](https://github.com/y20k/transistor/issues/361
)

	* SkyTube: [984](https://github.com/SkyTubeTeam/SkyTube/issues/984
)

	* aard2: [110](https://github.com/itkach/aard2-android/issues/110
)

	* Wikipedia: [5749](https://github.com/wikimedia/apps-android-wikipedia/commit/ab18c853b50ede7fae55b5a1803c57e9c6f606e8)

- Comparison with Genie:

	* Bugs detected by Odin alone:

		- Transistor: [265](https://github.com/y20k/transistor/issues/265), [230](https://github.com/y20k/transistor/issues/230)

		- Tasks: [741](https://github.com/tasks/tasks/issues/741)

		- UnitConverter: [217](https://github.com/physphil/UnitConverterUltimate/issues/217)

		- Markor: [1313](https://github.com/gsantner/markor/pull/1313)

		- AnkiDroid: [6284](https://github.com/ankidroid/Anki-Android/issues/6284)

		- AnyMemo: [512](https://github.com/helloworld1/AnyMemo/issues/512), [499](https://github.com/helloworld1/AnyMemo/issues/499)

	* Bugs detected by Genie only:

		- ActivityDiary: [261](https://github.com/ramack/ActivityDiary/issues/261), [288](https://github.com/ramack/ActivityDiary/issues/288), [289](https://github.com/ramack/ActivityDiary/issues/289), [291](https://github.com/ramack/ActivityDiary/issues/291)

		- Transistor: [235](https://github.com/y20k/transistor/issues/235)

		- Tasks: [816](https://github.com/tasks/tasks/issues/816)

		- UnitConverter: [170](https://github.com/physphil/UnitConverterUltimate/issues/170)

		- SimpleTask: [993](https://github.com/mpcjanssen/simpletask-android/issues/993)

		- Markor: [620](https://github.com/gsantner/markor/issues/620)

		- AnkiDroid: [5407](https://github.com/ankidroid/Anki-Android/issues/5407)

		- AnyMemo: [497](https://github.com/helloworld1/AnyMemo/issues/497), [496](https://github.com/helloworld1/AnyMemo/issues/496), [495](https://github.com/helloworld1/AnyMemo/issues/495)

		- MyExpense: [650](https://github.com/mtotschnig/MyExpenses/issues/650)

	* Bugs detected by Genie and Odin:

		- ActivityDiary: [286](https://github.com/ramack/ActivityDiary/issues/286), [287](https://github.com/ramack/ActivityDiary/issues/287), [290](https://github.com/ramack/ActivityDiary/issues/290)

		- Transistor: [234](https://github.com/y20k/transistor/issues/234), [236](https://github.com/y20k/transistor/issues/236), [239](https://github.com/y20k/transistor/issues/239),[249](https://github.com/y20k/transistor/issues/249)

		- Tasks: [811](https://github.com/tasks/tasks/issues/811)

		- UnitConverter: [201](https://github.com/physphil/UnitConverterUltimate/issues/201)

		- Fosdem: [47](https://github.com/cbeyls/fosdem-companion-android/issues/47)

		- Markor: [894](https://github.com/gsantner/markor/issues/894), [895](https://github.com/gsantner/markor/issues/895), [900](https://github.com/gsantner/markor/issues/900)
