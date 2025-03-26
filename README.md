# Making KoЯn-style nu-metal on Riffusion

![image](https://github.com/user-attachments/assets/bd8077d0-0658-4a7e-852f-e6c1fe3518f6)

My induction into the music world began when I was 8 years old and my brother made me listen to KoЯn - No place to hide, from the "Life is Peachy" album. It's been the centerpiece of my musical taste for the years to come, eventually leading me towards Slipknot and then opening up towards metal in general. A Riffusion contest organised by the community for reimagining "Mary had a little lamb" gave me the idea of trying to make some KoЯn in Riffusion, after all, Jonathan Davis does scream it 8 times in their 1994 song "Shoots and Ladders". If you're like me and you grew with metal and hip hop, you know that just like Wu-Tang, KoЯn is for the children.

In this tutorial, I will describe how I came to make "Evil and Oppression", a biblical poem by Isaiah 59, as if it was featured in the Family Values Tour of 1999.

## Note: Github doesn't automatically open links in new window, so please open links by either using middle-mouse click or right-click and open in a new tab.

Listen to the complete song here: https://www.riffusion.com/song/07f5e327-5217-4f57-a1d8-ab4a958bd3f1

## A little bit of music theory

Despite Pantera, Helmet and Faith No More being influential in the development of nu metal, KoЯn is often credited as pioneering the subgenre in the mid-1990s with their self-titled debut album. It features heavy and downtuned chugging guitar riffs with a raw, aggressive feel, while carrying some hip-hop undertones with the slap bass and sometimes rapped vocal delivery of the singer. The voice is dynamic and ranging from whispering, rapping, singing, screaming, and his iconic "scatting" style (e.g., "Ball Tongue"). The overall sound is heavy, groovy, but most importantly, it's especially _grimey and unpolished_, adding a dirty, organic, and visceral touch that makes it feel almost live and unfiltered.

One of the most recognizable and distinct feature of their style is the extensive use of _tritone-based chords_ (an interval spanning three whole steps, or augmented fourth/diminished fifth), which have a rich history of symbolism, namely for being associated with figures like the Devil. Without going into too much details, The tritone in Western music of the Middle Ages was considered too dissonant and was difficult to "resolve", and some theorists warned against its use in sacred music.

## Getting that "tritone" vibe

Now we don't have to exactly get an augmented fourth/diminished fifth, and to be honest, I don't know enough about music theory to really know when I'm hearing one, but really you're just trying to get a dissonant and panicky riff­. Since we do however know that KoЯn pioneered nu-metal and that tritone-based chords are a distinctive feature of the genre, let's just simply start with "90's nu metal, triton chords"

https://www.riffusion.com/song/2cfc0038-ea2c-4676-ab54-5ba4b1dc5b92

Oh yeah, it's a banger! There's a lot of non nu-metal stuff but listen to that intro! It's heavy, its chuggy, there's grime, there's dissonance... we're cooking!

## Extending and working the track

We'll try to extend it, starting from when the intro ends, and add some lyrics. I've added some "whispering weeping and oppressive vocals evoking themes of psychological torment and horror" and "scat-singing and explosive guttural screams Chrous" with hopes that it figures out that I'm trying to make something that would come out of an eyeliner-wearing queery goth white man with rastas having a nervous breakdown on stage.

- First try: https://www.riffusion.com/song/49368145-09ba-4bcd-918c-9a542c647a12
  - That ain't it. The lyrics are okay, not exactly what I'd expect for nu-metal, and when we get past the bridge it's starting to look more like a Bullet for my Valentine concert.
- 27th try: https://www.riffusion.com/song/70720efd-ec14-47d8-aa51-71939e108485
  - It feels like the more descriptive tags I add, the worse it gets. Either I don't know how to use this feature, or it could also just be that the FUZZ-0.8 model used at the time of this creation wasn't trained on nu-metal.

Riffusion users should remind themselves that it isn't forbidden to play around with the song outside Riffusion. In fact, it's low-key encouraged as Riffusion gives you everything you need; you can download the stems (a zip file with all the instruments of your song in individual tracks). With the stems, you can put your song in your favorite DAW (Digital Audio Workstation), chop samples, add effects, and essentially use the same techniques that a professional producer would use. I personally use FL Studio as I purchased it forever ago, but if you're not looking to buy, you can still work with the demo version (you will be able to export your track as a `.wav` or `.mp3` but you won't be able to save your project file).

## Getting the stems in our DAW

First, get the stems from Riffusion (see image) and put the content of the zip file in a project folder. The zip file always has four (4) `.m4a` files (a standard that Apple uses for delivering music tracks and other audio content from the iTunes Store). In our case those files will be for drums, bass, guitar and vocals, but if you're working with other kind of content, the names may vary.

![1](https://github.com/user-attachments/assets/fccf3730-3456-40d0-96d6-5ebc880b6128)

## Setting up our workflow

Since we're using a DAW, we should work with the correct tempo as this will make it easier to chop samples. I don't know the tempo of the song that I just made with Riffusion, so I'll have to guess it. In FL Studio, I'll right-click the tempo and click "Tap", then press play on the song. As I listen to the song, I'll tap any key on my keyboard on each beat, trying to be as synchronized as possible.

![2](https://github.com/user-attachments/assets/6e43a761-3de8-43a3-8095-03ec35a33541)

![3](https://github.com/user-attachments/assets/31dcc43a-5a65-467b-8f59-541fef2cf4c7)

![4](https://github.com/user-attachments/assets/a8ecbced-569a-45a0-844b-1fe475fd0eb3)

After tapping enough, I've determined that the tempo is probably 108. To ensure that this is right, we'll inspect our tracks from up close and align a drumkick transient with a line in our grid, though you should know that `.m4a` introduces a couple of millisecond of delay at the beginning of a track, so we'll start it on the 5th bar to account for that silence.

![5](https://github.com/user-attachments/assets/7d4ef52e-26e0-4cc7-9060-aabbbec792ab)

## Chopping samples

Okay looks like the tempo is good, we can work this track. The advantage of taking it off Riffusion is that you get to chop samples and reuse parts that you want. Consider the case of my first track; As much as I love it, I could never get the last chorus to be the same as the first chorus. See for yourself, listen to "Floating Point Style" and then compare all Choruses, you'll find that they say the same thing but the instrumental isn't the same from chorus to chorus: https://www.riffusion.com/song/c8b6e28a-154a-4701-ad1b-6da9e85945d6

Since we're working with a DAW now, we can chop the first chorus and reuse it whenever we need it. This ensures that our sound stays consistent throughout the track as it would with a so-called "real song". Ultimately, **we can also generate countless extensions from our base track** and then extract the stems, chop samples, rearrange, add new parts. We could even go beyond the 4:00 minutes limit though I am not sure that you would be able to upload your track on Riffusion thereafter.

Here's what I got going now:

![6](https://github.com/user-attachments/assets/1dc13d57-8cc0-4868-b6cd-78a44e4d9de0)

## Adding vocals

You may have noticed a vocal track on the last photo, despite the fact that we didn't have any good vocals to put. Since I couldn't get the creasy freaky Jonathan Davis whines in the voice, I figured I'd do it myself. I added a little reverb and distortion so that I could pretend that I was a real music producer.

[Isaiah 59.mp3
](https://baconwood.net/isaiah59.mp3)

The resulting version is "okay", but you can tell that I could use some more practice. My SM-58 microphone did a good job, but my voice doesn't feel like it's in front of the mix. I'm not really good at equalizing and mastering either (I used to be more into composing melodies), but if I can improve my crappy drawings with Stable Diffusion, surely I can improve my crappy voice with Riffusion?

## Making better vocals

If you've ever worked with image generation software like Stable Diffusion, you've likely heard of a concept called "denoising". When you take an image, you set the denoise at 50% and it's like telling the AI "use this image but you can only change 50% of it". I have come to understand that the Cover feature of Riffusion sort of works like that; if you set it to 15%, you only allow for 15% of variance. This should change the voice sufficiently enough for me to be unrecognizable while still preserving details like pitch, inflections, tone, pace, and articulation. Let's see what happens.

[Evil and oppression vocal fix.mp3
](https://baconwood.net/evil_and_oppression_vocal_fix.mp3)

Not bad but... Riffusion sort of destroyed all the surrounding music as well it seems. I don't think it's a limitation of Riffusion as much as it is a limitation of AI technology; we're allowing the AI to reshape 15% of _the entire song_, so naturally it does all the instruments. But that's okay! **Because we can extract the STEMS AGAIN!**

With the stems, we'll extract the vocals from the transformed song, and discard the rest. Then, we'll paste it over the original version that we worked on the DAW. Let's hear it now!

## Extending the song even more

Now it wouldn't be a KoЯn song without some nerve-wracking buildup of anxiety-inducing repetitive vocals that increase intensity. Let's see if I can sing over the song again and upload it to Riffusion, Cover it at 15% and see what happens. First, my singing part:

[intercede.mp3
](https://baconwood.net/intercede.mp3)

Now the new version:

[intercede2.mp3
](https://baconwood.net/intercedev2.mp3)

## Finishing touches

Well, all there's left now is to put it together and upload back on Riffusion. Usually I try to leave something to fix so I can upload it and use the replace or extend function to either fix some annoyance or extend the track to get the right ending. That's also a good time to fix any lyrics you may have written incorrectly or anything of the kind. Trim if necessary, add an image to the song. I can't remember the exact prompt but it went along the lines of "little girl looking out the window, there is a nu-metal concert happening in her backyard", combining the childlish imagery of "Follow the Leader" album and the narrative charge of "Falling away from me" as the girl escapes from her second floor bedroom, the crowd chanting and helping her out of it

https://youtu.be/2s3iGpDqQpQ?si=2CDfTOBtBXT4txoJ&t=260

At this stage you pretty much know everything that I did to get this to work exactly the way I wanted. Ultimately, while I worked on this, I learned that we shouldn't limit ourselves to one tool. But most importantly, we need to _iterate_ over and over and over again on what we have, take the bits that we like, and make a new creation from it. The Riffusion docs says it: "Building in this space requires a low ego. We are constantly learning, iterating, and listening to the needs of our community." Likewise we can learn, iterate, and use everything at our disposal to make our creative vision a reality.
