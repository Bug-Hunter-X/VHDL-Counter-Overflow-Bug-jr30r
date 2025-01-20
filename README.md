# VHDL Counter Overflow Bug and Fix

This repository demonstrates a common but subtle error in VHDL code: integer overflow in a counter.  The `buggy_counter.vhdl` file contains a counter that increments until it reaches 15 and then resets. However, if the counter accidentally goes beyond 15 (due to unforeseen circumstances), it will result in undefined behavior.

The `fixed_counter.vhdl` file provides a corrected version that handles the potential overflow gracefully.