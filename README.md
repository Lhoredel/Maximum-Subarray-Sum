# Maximum-Subarray-Sum
This code solves the Maximum Subarray Sum problem using modular arithmetic to find the subarray with the maximum sum modulo m. It uses a prefix sum approach with a sorted set to efficiently track previous prefix sums and find optimal subarray boundaries. The algorithm maintains a running prefix sum and searches for the smallest higher prefix sum to maximize (prefix[i] - prefix[j]) % m, ensuring optimal performance with O(n log n) complexity.

