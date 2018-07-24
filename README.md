# Listening test on the effect of phase in the context of source separation

This is a listening test interface based on Web Audio Evaluation Tool (WAET):

> Nicholas Jillings, Brecht De Man, David Moffat and Joshua D. Reiss, "[Web Audio Evaluation Tool: A Browser-Based Listening Test Environment](http://smcnetwork.org/system/files/SMC2015_submission_88.pdf)," [12th Sound and Music Computing Conference](http://www.maynoothuniversity.ie/smc15/), July 2015.

The original repository can be found [here](https://github.com/BrechtDeMan/WebAudioEvaluationTool).

## Instruction (local test)

At this stage it's only possible to run it locally.

1. Download or clone the whole repository

2. Go to the `[WAET-home-folder]/python` folder and run `pythonServer.py` (Python 2.7 required for some reason!)

3. Open a web browser (Chrome or Firefox recommended) and type

	localhost:8000/test.html?url=tests/phasetest.xml

4. Input your ID (initials preferred) and start the test

5. When you finish, the result will be saved as an xml file in `[WAET-home-folder]/saves`. Identify the correct result file by the modified time or the ID you put inside the xml file (open the xml and use the find feature in any text editor).


## WAET License

Please refer to LICENSE.txt ([GNU General Public License](http://www.gnu.org/licenses/gpl-3.0.en.html)).
