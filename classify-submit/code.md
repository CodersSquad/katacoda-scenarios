It's time for the fun part. We'll be working in the `test-lab` that is
prepared in your class repository. Let's move to that directory.

`cd labs/test-lab`{{execute}}

All labs will container 4 common files:

- `Makefile` - Includes Classify automation commands. You don't need
  to modify it.
- `lab.mk` - Includes lab specific automation commands
  (i.e. compilation, test). You don't need to modify it.
- `README.md` - Includes lab's instructions.
- `<source_code_file(s)>` - It can be one or multiple files, this is
  where you will be coding your lab's solution. Make sure that you
  work only on this file. Don't create new source code files.


## Let's code

AS promised at the beginning, it's time for the fun. Let's code.

- Open the instructions file in the Katacoda Editor.

**Advanced Programming class**

`ap-labs/labs/test-lab/README.md`{{open}}


- You ready to code? let's open the source code file and implement the
solution to this lab.

**Advanced Programming class**

`ap-labs/labs/test-lab/test-lab.go`{{open}}

- Are you done? OK, don't forget to test it a thousand times.

Most of the labs will include the proper automation to test it, check
the `README.md` file, it will indicate how your program should be
tested.

This last part is really important, this is going to be how the Classify
API will test your app. So, make sure that your application runs with
the provided test cases.

``make test``{{execute}}

Is it running as expected? cool. That's all, let's go to the submit section.
