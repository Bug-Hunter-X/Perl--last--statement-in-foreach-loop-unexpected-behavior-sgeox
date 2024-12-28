# Perl 'last' Statement Gotcha

This repository demonstrates a common error involving the 'last' statement in Perl's 'foreach' loop. The example code is designed to print numbers from 1 to 4, but because of the 'last' statement, it terminates early. This illustrates an important aspect of Perl's loop control flow. The solution shows how to correctly achieve the intended output.

## How to run the code:

1. Save the code in `bug.pl` and `bugSolution.pl`.
2. Run the Perl scripts from your terminal:
   ```bash
   perl bug.pl
   perl bugSolution.pl
   ```

The `bug.pl` script will exhibit the unintended behavior. The `bugSolution.pl` will demonstrate the corrected approach.