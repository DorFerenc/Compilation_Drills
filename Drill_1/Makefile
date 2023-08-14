build:
	flex college.lex
	gcc lex.yy.c -o college_lex -lfl

clean:
	rm -f college_lex lex.yy.c

run:
	./college_lex input.txt

runBad:
	./college_lex input_bad.txt

