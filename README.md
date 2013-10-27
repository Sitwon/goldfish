goldfish
========

An elephant never forgets; a goldfish never remembers.

This is a tool for creating secure, temporary storage. It does this by mounting a loopfile that has been encrypted with a random key. Since the key is never revealed, once the filesystem is unmounted or the system is shutdown the data becomes unrecoverable.

This requires the cryptoloop kernel module to be loaded.
