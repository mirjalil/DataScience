CPPFLAGS=-std=c++11 -g -O3


Sort: main_list.o main_stack.o main_queue.o main_deque.o main_tree.o \
      main_bst.o
	g++ main_list.o -o runlist
	g++ main_stack.o -o runstack
	g++ main_queue.o -o runqueue
	g++ main_deque.o -o rundeque
	g++ main_tree.o -o runtree
	g++ main_bst.o -o runbst

main_list.o: main_list.cpp
	g++ $(CPPFLAGS) -c main_list.cpp

main_stack.o: main_stack.cpp
	g++ $(CPPFLAGS) -c main_stack.cpp

main_queue.o: main_queue.cpp
	g++ $(CPPFLAGS) -c main_queue.cpp

main_deque.o: main_deque.cpp
	g++ $(CPPFLAGS) -c main_deque.cpp

main_tree.o: main_tree.cpp
	g++ $(CPPFLAGS) -c main_tree.cpp

main_bst.o: main_bst.cpp
	g++ $(CPPFLAGS) -c main_bst.cpp

clean:
	rm *.o -f
