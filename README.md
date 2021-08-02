# pulga C++ Library
Pulga is a C++ Lib. , That's aim to make simple task and difficult task impossible
Each file is has a read.txt documentationl section of how it works, and each file represent a type

eg:
  #include"pulga_memory" // contains {stack, heap, readonly , entangle, s_Array, h_Array}
  #include"pulga_math" // contains  {number, shape, cNum, constant, log};
  
  
Types in Pulga are designed to work with built-in 
eg:
  int b = 10;
  pulga::stack x{10}; 
  pulga::stacl y{b};
  x == y // true

  
