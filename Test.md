# Test H1
## Test H2
## Test Code
```cpp
#include <bits/stdc++.h>
using namespace std;

void solve() {
	int n;
	cin >> n;
	vector<int> a(n);
	int mi = INT_MAX, mx = 0;
	for (int i = 0; i < n; i++) {
		cin >> a[i];
		mi = min(mi, a[i]);
		mx = max(mx, a[i]);
	}
	cout << (mi == mx ? n : 1) << "\n";
}

int main() {
	int t;
	cin >> t;
	while (t--) solve();
}
```
