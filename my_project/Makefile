prep: scripts/prep_data.sh
	./$<

clean:
	rm -r data

all: prep clean

help:
	@echo "make prep  - Run data preparation"
	@echo "make clean - Remove data files"
	@echo "make all   - Clean + Prep"
