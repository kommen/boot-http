# 0.5.0

- Fix: directory listings and files take precedence over resources with :dir option
- Add: -k/--httpkit option to use Http-kit instead of Jetty

# 0.4.2

- Fix: create a pod for each task instance instead of sharing one

# 0.4.1

- Add -r/--resource-root to specify a route prefix for resources

# 0.4.0

- Remove -b/--block option (use wait instead)
- Add -H/--handler to serve a ring handler
- Bump boot to 2.0.0-rc5