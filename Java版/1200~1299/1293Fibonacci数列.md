```Java
/**
 * Time 178ms
 * @author wowpH
 * @version 1.3
 * @date 2019年5月27日下午9:41:25
 * Environment:	Windows 10
 * IDE Version:	Eclipse 2019-3
 * JDK Version:	JDK1.8.0_112
 */

import java.util.Scanner;

public class Main {
	public static void main(String[] args) {
		int MAXN = 1000000;
		int MOD = 10007;
		int[] f = new int[MAXN + 1];
		f[1] = f[2] = 1;
		for (int i = 3; i <= MAXN; i++) {
			f[i] = (f[i - 1] + f[i - 2]) % MOD;
		}
		int n;
		Scanner sc = new Scanner(System.in);
		while (sc.hasNext()) {
			n = sc.nextInt();
			System.out.println(f[n]);
		}
		sc.close();
	}
}
```