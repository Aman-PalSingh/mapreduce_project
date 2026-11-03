# MapReduce Latency Demo

This project uses a simple MapReduce workflow in Node.js to count latency values under 10,000 and at least 10,000.

## Run

From the project root:

```bash
chmod +x run.sh
./run.sh
```

The final counts are written to `reduce_results/results.txt` and printed in the terminal.

## Important note about the input values

The `host1/latencies.txt` and `host2/latencies.txt` files contain the values legible in the screenshots provided. The screenshots show only the visible portion of each long file, so values below the visible area could not be reconstructed. Replace/append the remaining original values if you need the complete original dataset.
