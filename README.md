# Loco hack
A python script that helps to play loco trvia game real time.
### How to setup

1. Download appropriate [python 2](https://www.python.org/downloads/) based on your system
2. Install the file and select `Add to path`  during installation. This will make it easier to run the file whenever needed
3. Check succesful installation by typing
```sh
py -0
```
You should get an output like this
```sh
Installed Pythons found by py Launcher for Windows
 -2.7-64 *
```
4. Now run the following command
```sh
$ pip3 install -r requirements.pip
```
5. Obtain required API keys from Google and replace them in the play.py
    1.  YOUR_GOOGLE_API_KEY - [Google cloud API key](https://support.google.com/cloud/answer/6158862?hl=en) (at line 16)

    2. GOOGLE_SEARCH_ENGINE_ID - [Custom search engine id](https://support.google.com/customsearch/answer/2630963?hl=en) (at line 17)
6. Enable `USB Debugging` in [Developer settings](https://www.digitaltrends.com/mobile/how-to-get-developer-options-on-android/) of your phone and connect it to the PC
7. Open Command Prompt or any other shell to initialise your phone to transfer data to the program
8. Enter `adb devices` and hit enter. This will pop up a dialog in the phone
9. Slecet Always Allow and click on ok on the phone. Now run the above command again.
This time it will show something like
```sh
List of devices attatched
<random something> device
```
10. Now your phone is set up successfully. Test the hack by running `py play.py`
