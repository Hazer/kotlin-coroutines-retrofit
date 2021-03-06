# CHANGELOG

## Version 0.3.0 (2017-02-25)

- [Retrofit 2.2.0](https://github.com/square/retrofit/blob/parent-2.2.0/CHANGELOG.md#version-220-2017-02-21). Also it is minimum supported version
- [kotlinx.coroutines 0.11-rc](https://github.com/Kotlin/kotlinx.coroutines/releases/tag/0.11-rc)
- Custom HttpError class replaced with [HttpException](https://github.com/square/retrofit/blob/parent-2.2.0/retrofit/src/main/java/retrofit2/HttpException.java) from Retrofit 2.2

## Version 0.2.0 (2017-02-20)

- Depends on Retrofit 2.1.0
- Result classes now implement one or two of interfaces: ResponseResult and ResponseError. It allows simplify access to results in some cases
- Moved to the separate repo
- Kotlin 1.1.0-rc-91
- kotlinx.coroutines 0.10-rc
- JCenter and Maven publish configs
- Updated examples in readme