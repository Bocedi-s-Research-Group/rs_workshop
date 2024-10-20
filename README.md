# RangeShifter Workshop

Workshop material to run exercises 4 and 5 of the RangeShifter user manual using the batch mode of RangeShifter v3.0, including the new genetics module.

## Contents

This repo contains:

- Ready-made project directories for exercise 4 and exercise 5, including the Inputs, Output_Maps and Outputs subfolders required by RangeShifter

- The initial input files for Exercise 4, and the solutions for the completed exercise.

- Solutions for exercise 5

- The RangeShifter User Manual

- Documentation for the input files in the form of Excel spreadsheets and for the Control file.

- The RangeShifter batch executable (release mode)

- A test project to control the RangeShifter executable runs correctly

## Running RangeShifter



After cloning or downloading this repository, open the Windows PowerShell or a Unix shell and navigate to the location of this repository with the `cd` command.

To run the executable, simply type `.\RangeShifter.exe <path_to_project_dir>`

where `<path_to_project_dir>` is a path to a directory containing the Inputs, Outputs and Output_Maps subfolder.

Before getting started with RangeShifter, make sure that the executable runs correctly on the `test` project provided:

```shell
.\RangeShifter.exe .\test\
```

The output should display

```shell
RangeShifter Release Mode

Batch input files OK
```

If you get something else, talk to one of the workshop facilitators. Otherwise, you're all set!
