
default: osmo-bsc-lchan-alloc.png

%.png: %.msc
	mscgen -T png $<

.PHONY: poll
poll:
	while true; do $(MAKE) osmo-bsc-lchan-alloc.png; sleep 1; done

