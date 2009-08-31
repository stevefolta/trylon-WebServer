# Makefile for a Trylon program.

PROGRAM := web-server-test


SOURCES := main $(wildcard ../*) $(wildcard sources/*) $(wildcard build-settings) $(wildcard build-settings.local)


all: runnit


$(PROGRAM): $(SOURCES)
	@trylon
	@echo "---------------------------------------------"
	@echo


.PHONY: runnit
runnit: $(PROGRAM)
	@./$(PROGRAM)

