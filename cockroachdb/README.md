docker run -d `
--net=roachnet `
-p 26257:26257 -p 8080:8080 `
cockroachdb/cockroach:v1.0.3 start --insecure