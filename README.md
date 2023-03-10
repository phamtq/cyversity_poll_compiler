# Cybersity Poll Data Compiler
This project is aimed at transforming the raw poll data posted in the Slack channel into useful information using shell (bash) scripting. The aim of the project is make it easier compile this data, ask questions, and use code to answer them.

## Installation

To install this project, you can clone the GitHub repository to your local machine:

```
git clone https://github.com/phamtq/android_configurator_lite.git 
```

Once you have cloned the repository, you may need to make sure you have bash installed on your system.

## Usage
To use this script, either change the permissions of the file (Linux, Mac, etc...):

```
chmod 755 ./cycompile
```

or invoke bash every time you want to run the script:

```
bash ./cycompile <options>
```

Run the script with the *init* option first to create the files that you'll be copying and pasting into from the Slack poll.

```
./cycompile init
```

After you've copied and pasted the information into the various file according to the cybersecurity field use the *run* option to compile the data into something useful. 

```
./cycompile run
```

Some useful questions may be already added to the script along with the accompanying code. Feel free to modify and add your own in order to answer your own questions.  

## Contributing

If you would like to contribute to this project, please fork the repository and create a new branch for your changes. Once you have made your changes, create a pull request, and we will review your changes.

## Credits

This project was created by Timothy Q Pham.

## License

This project is licensed under the GNU General Public License. See the LICENSE file for more information.
