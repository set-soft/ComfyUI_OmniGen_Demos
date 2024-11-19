# What is depth map for the model?

Looking at the authors example it looks like the model knows about depth maps.
So I tried this:

prompt:

```
Depth map of image_1
```

image_1:

![image](../../inputs/original/t2i_woman_with_book.png)

- Steps: 10
- Resolution: 1024x1024
- Guidance: 2.5/1.6
- Seed: 0
- Workflow: [OmniGen_00006__workflow.json](OmniGen_00006__workflow.json)

![image](OmniGen_00006_.png)

This isn't exactly what I understand by a depth map, but is quite interesting
