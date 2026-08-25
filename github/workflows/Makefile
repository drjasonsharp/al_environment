TARGET ?= hello

$(TARGET): $(TARGET).o
	ld $(TARGET).o -o $(TARGET)

$(TARGET).o:
	nasm -f elf64 -g -F dwarf $(TARGET).asm -o $(TARGET).o

run: $(TARGET)
	./$(TARGET)

clean:
	rm -f *.o hello lab*