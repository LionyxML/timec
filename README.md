# timec - Terminal Count-Up Timer

timec is a simple shell script that allows you to create count-up timers directly from your terminal. It provides options to label the timers and run stopwatch functionality for a specified duration.

## Usage

```
./timec [option]
```



### Options

- `--label "Text"`: Labels the timer with the specified text.
- `-s <minutes>`: Runs a stopwatch for the specified number of minutes and notifies upon completion.
- `--help`: Displays the usage information.
- `--version`: Displays the current version of the script.

## Examples

### Start the Timer

```
./timec
```

### Start a Timer with Label
```
./timec --label "Kitchen Timer"
```

### Start a Stopwatch for 5 Minutes

```
./timec -s 5
```

### Start a Stopwatch for 5 Minutes with Label

```
./timec -s 5 --label "Exercise"
```
OR 
```
./timec --label "Exercise" -s 5
```

