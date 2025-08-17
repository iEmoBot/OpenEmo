To recreate the defaultEye.h file, you’d go the “convert” directory and enter this command (as a single line):

python tablegen.py defaultEye/sclera.png defaultEye/iris.png defaultEye/lid-upper-symmetrical.png defaultEye/lid-lower-symmetrical.png defaultEye/lid-upper.png defaultEye/lid-lower.png 80 > defaultEye.h



