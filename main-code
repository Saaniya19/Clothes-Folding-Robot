import RPi.GPIO as GPIO
import time

#defining the board type we are using to number the pins
GPIO.setmode(GPIO.BOARD)

#setting each of the following pins as outputs
GPIO.setup(11, GPIO.OUT)
GPIO.setup(12, GPIO.OUT)
GPIO.setup(13, GPIO.OUT)
GPIO.setup(16, GPIO.OUT)
GPIO.setup(15, GPIO.OUT)
GPIO.setup(18, GPIO.OUT)

#setting the pulse frequency for each pin
servo 1A = GPIO.PWM(11, 20)
servo 1B = GPIO.PWM(12, 20)
servo 2A = GPIO.PWM(13, 20)
servo 2B = GPIO.PWM(16, 20)
servo 3A = GPIO.PWM(15, 20)
servo 3B = GPIO.PWM(18, 20)

#setting initial PWM
servo1A.start(1)
servo1B.start(8)
servo2A.start(1)
servo2B.start(8)
servo3A.start(1)
servo3B.start(8)

time.sleep(2)

print("Changing duty cycle")
servo1A.ChangeDutyCycle(8)
servo1B.ChangeDutyCycle(1)
time.sleep(2)
servo1A.ChangeDutyCycle(1)
servo1B.ChangeDutyCycle(8)
time.sleep(2)

print("Changing duty cycle")
servo2A.ChangeDutyCycle(8)
servo2B.ChangeDutyCycle(1)
time.sleep(2)
servo2A.ChangeDutyCycle(1)
servo2B.ChangeDutyCycle(8)
time.sleep(2)

print("Changing duty cycle")
servo3A.ChangeDutyCycle(8)
servo3B.ChangeDutyCycle(1)
time.sleep(2)
servo3A.ChangeDutyCycle(1)
servo3B.ChangeDutyCycle(8)
time.sleep(2)

servo1A.stop()
servo1B.stop()
servo2A.stop()
servo2B.stop()
servo3A.stop()
servo3B.stop()
GPIO.cleanup()
print("Done")
