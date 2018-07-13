BIN := /usr/bin
PRINTF := $(BIN)/printf
DF := $(BIN)/df
AWK := $(BIN)/awk

define free-space
	$(PRINTF) "Free disk space "
	$(DF) . | $(AWK) 'NR == 2 { print $$4 }'
endef

OUTPUT_DIR := /tmp

$(OUTPUT_DIR)/very_big_file:
	$(free-space)

