# socialized media

A spefication, example, and demo for the syndication and publishing
of social media, articles, and other internet artifacts. This
specification intends to enable users to own and control their data
while facilitating its subscription and aggregation.

## rationale

There are a small number of companies / apps / sites that hoard and
profit from user content. The users don't own their content, and
can't easily extract it. By operating within these walled gardens,
companies restrict the rights of the majority of social media users,
who do not currently have a means of existing on their own outside
of Facebook, Twitter, Instagram, etc.

This project intends to speculate on a specification to empower
users to own their own data, and demo a set of tools using this
specification such that that data could be subscribed to, aggregated,
added to, and managed.

## goals

1. people control their public social data, its storage
2. simple, easy to implement specification using existing technologies
3. minimal data size / network traffic for update check
4. just enough manifest for recent entries
5. aggregators can access a person's public data in a consistent way
6. tampering with social data is detectable via content hashing
7. tampering with archive is detectable via archive hashing
8. spec should encourage the development of supporting 3d party apps
9. data should be stored (when unpacked) in human-readable format
7. choice of storage media should be immaterial
8. people and every element of their data should be addressable as a url
9. spec simple enough to use text editor and file system

## demo / supporting apps / proofs of concepts

1. command line content packer
2. extract archive into blog
3. aggregate content from list of syndicated archives
4. identity/address index for users' content (search for friends)

## roadmap

TBD

