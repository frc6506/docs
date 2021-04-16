# Robot Characterization with the frc-characterization utility

## To install

1. Install the latest version of Python 3.7
    > Note: The latest version of [Python 3.7.10](https://www.python.org/downloads/release/python-3710/), but there is no official binary available.  Instead, we can use Python 3.7.9, which can be downloaded at [python.org/downloads](https://www.python.org/downloads/release/python-379/).

2. If you have multiple version of Python installed, you will need to use the following command to install the `frc-characterization` utility from `pip`.

    ```CMD
    %USERPROFILE%\AppData\Local\Programs\Python\Python37\python.exe -m pip install frc-characterization
    ```

## To run

1. If you have multiple version of Python installed, you will need to use the following command to run the `frc-characterization` utility with the correct Python version.

   ```CMD
   %USERPROFILE%\AppData\Local\Programs\Python\Python37\python.exe %USERPROFILE%\AppData\Local\Programs\Python\Python37\Lib\site-packages\frc_characterization\__main__.py
   ```

2. When prompted to "Choose which mechanism you are characterizing", enter `1` for drive

3. When prompted with "Characterization Tools: drive", enter `1` for new, which will take you to the main window.

## Further Instructions and Additional Information

See [https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/robot-characterization/index.html](https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/robot-characterization/index.html) for a general overview and step by step details.
> Note that this guide assumes that one _only_ has Python 3.7 installed, with no other Python installations alongside it.  The purpose of the above sections are to assist with this.

<br>
[Site Index](https://frc6506.github.io/docs/index)

<br>
_Updated 20210323T1030 PT_
