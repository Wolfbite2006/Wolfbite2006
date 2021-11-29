from djitellopy import Tello
from time import sleep

tello = Tello()

#connection and takeoff
tello.connect()
tello.takeoff()

#1-3
tello.move_up(101)
sleep(.01)
tello.move_forward(182)
sleep(.01)
tello.rotate_counter_clockwise(90)
sleep(.01)

#4-5
tello.move_forward(182)
sleep(.01)
tello.rotate_clockwise(90)
sleep(.01)

#-6-7
tello.move_down(91)
sleep(.01)
tello.move_forward(91)
sleep(.01)
tello.rotate_counter_clockwise(90)
sleep(.01)

#8-9
tello.move_up(30)
sleep(.01)
tello.move_up(91)
sleep(.01)
tello.rotate_clockwise(90)
sleep(.01)

#10-11
tello.move_forward(122)
sleep(.01)
tello.land()
