include ../Config

run: simon.tap
	$(EMULATOR_PATH) simon.tap $(EMULATOR_OPTS)

simon.tap: simon.bas
	$(BAS2TAPE_PATH) -a 1 -o simon.tap -n simon simon.bas

clean:
	rm -f simon.tap
