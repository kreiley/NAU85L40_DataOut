CC = gcc

TARGET = Beamforming

all: $(TARGET)

$(TARGET): $(TARGET).c
	$(CC) -g -o $(TARGET) $(TARGET).c FixedBeamformer.c delay_sound.c localization.c -lm

clean: 
	$(RM) $(TARGET)
