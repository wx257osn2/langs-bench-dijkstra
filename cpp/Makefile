all: main

clean:
	rm main

main: src/main.cpp
	g++ -std=c++2a -O3 -Wall -Wextra -Wno-maybe-uninitialized -pedantic-errors -march=native -mtune=native -I external_projects/robin-hood-hashing/src/include -I external_projects/fast_io/include -o main src/main.cpp
