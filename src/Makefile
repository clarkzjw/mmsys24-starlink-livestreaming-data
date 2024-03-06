all:
	mkdir -p figures/streaming figures/latency
	poetry run python plot-bitrate.py
	poetry run python plot-live-latency.py
	poetry run python plot-rebuffering.py
	poetry run python plot-bitrate-switch-count.py
	poetry run python plot-qoe.py
	cd latency && poetry run python figure2.py
	cd latency && poetry run python figure3.py