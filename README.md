### Deep dive to neural networks, lessons from Andrej Karpathy's makemore series.

**PART 1**

Plowing through the first part. 

https://www.youtube.com/watch?v=PaCmpygFfXo&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=2

I got a decent performance upgrade on my laptop using my puny Nvidia Quadro RTX 3000 GPU running the optimizations.

**PART 2**

I torched my GPU, so no more of that.

On part 2 exercizes, i got as low as ~2.15 with the loss, but it didnt seem to make much difference for the values under 2.3. I sat in front of the screen for a little too long and started to haphazardly punching values with no consistency, and i changed multiple hyperparameters on same runs, and i didn't log them all, so this was not really thought out exercize from my part. Fun it was never the less.

The "names" are exotic, but more name-like than with the bigram model. I got a couple good names though: Shania and Sandra for the ladies, and my favourite for the boys: Brick.

**PART 3**

Kaimin initialization and batch normalization + visualizing intermediate steps during training. This was an eye opening lesson, though i should also read through and (try to) understand the theory behind all this. Working with tensors, let alone with huge amount of parameters makes the forward-backward-passes hard to understand. You just have to accept the cumulative nature of learning, especially with maths, and revise these later again.