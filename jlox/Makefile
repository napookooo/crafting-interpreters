src_dir = src
out_dir = out
main = com.cuzof.lox.Lox
target = main.lox

make:
	mkdir $(out_dir)
	javac -d $(out_dir) $$(find $(src_dir) -name *.java)

clean:
	rm -rf $(out_dir)

run:
	java -cp $(out_dir) $(main) $(target)

manual:
	java -cp $(out_dir) $(main) 
