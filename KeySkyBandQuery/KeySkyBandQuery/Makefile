cc=gcc
exe=main
obj=main.o BucketVector.o PointVector.o
$(exe):$(obj)
	$(cc) -g -Wall -o $(exe) $(obj)
main.o:main.c BucketVector.h PointVector.h 
	$(cc) -c main.c
BucketVector.o:BucketVector.c BucketVector.h
	$(cc) -c BucketVector.c
PointVector.o:PointVector.c PointVector.h
	$(cc) -c PointVector.c
clean:
	rm -rf *.o

