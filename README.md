# YouTube playlist

## Tools

### play with playlist files

The below command make a HTML for `playlist1` and `playlist2` in `shuffle mode`, save as `/tmp/out.html`, then `open` the HTML.

```bash
./play -o /tmp/out.html --open --shuffle playlist1 playlist2
```

### make playlist from `/playlist` page

```bash
./vget 'https://www.youtube.com/playlist?list=PLV1VKKSui4LHL2aiQV-K_CLg6bwj45u-F' > playlist
```

### fetch a video

```bash
./vget 'https://www.youtube.com/watch?v=kZmk8PxjhnY'
```

### N.B.

`vget` command deal with the url as playlist page if the url contains `list=`.

