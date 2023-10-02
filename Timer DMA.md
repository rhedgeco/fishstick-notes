Four modes:
- Input Capture
- Output Compare
- PWM
- Single pulse

Three important numbers:
- `0`
- Compare value
- Max value

Counter register

Timer increments the counter register each cycle. 

In PWM mode, 
- while `Counter < Compare`, output is low. 
- while `Counter > Compare`, output is high
- These can be swapped and there are more complicated things to do

In Output Compare mode
- Actions can be triggered when `Counter >, <, = Compare` 
- 