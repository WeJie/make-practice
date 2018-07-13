VPATH = src include
CPPFLAGS = -I include

count_words: counter.o lexer.o -ll
count_words.o: counter.h
counter.o: counter.h lexer.h
lexer.o: lexer.h

