from djitellopy import Tello

tello = Tello()
tello.connect()

sleep(1)
tello.takeoff(106.68)

sleep(1)
tello.move_up(76.2)

sleep(1)
tello.move_left(304.8)

sleep(1)
tello.move_back(30.48)

sleep(1)
tello.move_forward(304.8)

sleep(1)
tello.flip_forward(30.48)

sleep(1)
tello.move_left(304.8)


tello.land()
tello.end()
