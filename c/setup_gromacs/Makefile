# マクロ定義
CXX			= g++
CXXFLAGS	= -O3 -lm
LDFLAGS		= 
INCLUDES	= -I.
TARGET		= setup_gromacs
OBJS		= setup_gromacs.o

# 生成規則
$(TARGET): $(OBJS)
	$(CXX) $(LDFLAGS) -o $@ $(OBJS) $(LIBS)

clean:
	-rm -f $(TARGET) $(OBJS) .nfs* *~ \#* core

.c.o:
	$(CXX) $(CFLAGS) $(INCLUDES) -c $<


