# AWS LambdaをSpringBootで実装する（RDBなし版）
## 目的とか背景とか
- LambdaにSnapStartが実装されたので、やっとLambdaでJavaを使って良さそうだなと思った
  - 実際PureJavaでのLambda実装は何度かやっている
- Webアプリの場合はSpringBootを使うので、Lambdaでもなるべく同じコードを書きたい
## キーになるソフトウェア(2024-08-03調べ)
| Name | Latest version |
| ---- | ---- |
| Java (LTS) | 21 |
| LambdaのJavaランタイム | 21 |
| Spring Boot | 3.3.2 |
| Spring Cloud Function | 4.1.3 |
| Spring Native | ?? |
