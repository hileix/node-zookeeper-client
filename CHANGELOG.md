# Change Log

## 1.2.0
1. Expose State Connecting so that it could control the retries outside somewhere to avoid the [Issue #30: infinite connect retries](https://github.com/alexguan/node-zookeeper-client/issues/30)
2. Fix vulnerability found by audit

## 1.1.0

1. [New: Add removeRecursive and listSubTreeBFS methods](https://github.com/alexguan/node-zookeeper-client/pull/88)
2. Upgrade eslint and mocha dependencies
3. Bump Node requirement to >=8.10.0

# 1.0.0

1. [Issue #92: Remove use of deprecated Buffer() constructor](https://github.com/alexguan/node-zookeeper-client/issues/92)

## 0.2.3

1. [Issue #64: Error when using from react](https://github.com/alexguan/node-zookeeper-client/issues/64)

## 0.2.2

1. [Issue #31: WatcherManager leaks memory on un-rewatched nodes](https://github.com/alexguan/node-zookeeper-client/issues/31)

## 0.2.1

1. [Issue #19: Prevent duplicated watcher from being added](https://github.com/alexguan/node-zookeeper-client/pull/19)

## 0.2.0

Initial release.
