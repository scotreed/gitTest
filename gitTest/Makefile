CXXFLAGS =	-O2 -g -Wall -fmessage-length=0

OBJS =		gitTest.o

LIBS =

TARGET =	gitTest

$(TARGET):	$(OBJS)
	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)

all:	$(TARGET)

clean:
	rm -f $(OBJS) $(TARGET)
