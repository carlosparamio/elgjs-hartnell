include ../Config

run: emboscada.tap
	$(EMULATOR_PATH) emboscada.tap $(EMULATOR_OPTS)

emboscada.tap: emboscada.bas
	$(BAS2TAPE_PATH) -a 1 -o emboscada.tap -n emboscada emboscada.bas

clean:
	rm -f emboscada.tap
