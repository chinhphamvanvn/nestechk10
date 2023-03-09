- git thì có branch là main.
- branch develop là branch cho developer phát triển
- branch release là branch cho product(branch đã được người dùng sử dụng)
- branch sit là branch cho bộ phận kiểm thử(tester)
- branch uat là branch cho bộ phận nghiệp vụ(tester chuyên về nghiệp vụ)
- khi lấy repo về thì thường ở branch develop. Sau đó mình checkout sang một nhánh mới
thì nhánh mới đó sẽ được copy tất cả code của branch develop

- git checkout -b feature/ten-tinh-nang (checkout from develop)
- git checkout -b bugfix/ten-bug (checkout from develop)
- git checkout -b hotfix/ten-hot-fit (checkout from release)

- git checkout -b exercises/username-exercise1