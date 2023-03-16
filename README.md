# alaram
alaram.code
import time
import winsound

# set the duration of the alarm in seconds
duration = 5

# wait for the specified duration
time.sleep(duration)

# play a sound when the alarm goes off
winsound.Beep(440, 1000) # 440 Hz frequency for 1 second
