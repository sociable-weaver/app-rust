# Sociable Weaver

The [Sociable Weaver webpage](https://sociable-weaver.github.io/web/) expects this application to be running on the
users' computer. The [Sociable Weaver Application Java Application](https://github.com/sociable-weaver/app-java-boot) is
the official implementation of the application and it is feature complete. This is another version of the experimental
application written in Rust.

I am learning Rust and I wanted to experiment a bit and used this application as an example. This is not an official
application and may be incomplete.

## Useful commands

Git

- Commit changes

  ```shell
  $ git commit -m "Add tag example"
  ```

- Push changes to _origin_

  ```shell
  $ git push
  ```

- List all tags

  ```shell
  $ git tag
  ```

- Tag the current commit and push to _origin_

  ```shell
  $ git tag v0.1
  $ git push origin v0.1
  ```

  This will trigger the build pipeline and release the application. Note that the tag needs to be unique.
