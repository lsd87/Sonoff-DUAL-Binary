# Sonoff-DUAL-Binary
Stefanbode Sonoff DUAL Binary

This is Stefanbode Binary with the Sonoff DUAL changes to make BOTH Buttons work 
Just here to help people who don't want to recompile from scratch

Only changes to Stefans code was GPIO010 value as below

"sonoff_template.h, in section Sonoff Dual R2, replace the line
GPIO_KEY1, // GPIO10 Button on casing with 
0, // GPIO10 Button on the casing
then in configure module section you're able to select button 1 for GPIO0 (before was not available), and button 2 for GPIO9"
