# A Practical Guide to Fix AI Hands With Hand Fix, Repaint, and Reference Pro

We tested Hand Fix, inpainting, and Reference Pro to fix AI hands in PixAI, and checked which ones kept the rest of the image intact.

<img width="1672" height="941" alt="Blog header for a guide on how to fix AI hands, showing a lilac-haired anime tea shop owner holding a notebook beside three examples: malformed fingers, an awkward teacup grip, and tangled hands." src="https://github.com/user-attachments/assets/e46bd052-8422-4d8b-a109-b1b5bc36a4eb" />

*We fixed three common AI hand problems in PixAI without redrawing the character.*

A dead giveaway that you’re looking at AI art is usually the hands. The hair, the eyes, and the background can all look perfect, and then you spot a finger bending the wrong way or a thumb in the wrong place.

One bad hand can ruin an illustration you otherwise love, and regenerating it could cost you every detail that was already right. So how do you fix AI hands without starting from scratch?

Well, let’s take a step back and figure out what kind of problem you’re dealing with. Sometimes the anatomy is off, with extra, missing, or fused fingers. Sometimes the hand is holding a cup or prop in a way that looks awkward. And sometimes the hand is just partly hidden, which isn’t a mistake at all. A hand doesn’t need five visible fingers to look natural.

To find out whether it’s possible to fix hands in AI art without changing the rest of the image, we created Mira, a tea blender who runs a small glasshouse shop. We generated her in three everyday moments with Tsubaki.3 in PixAI, an AI art platform built for anime creators, and each one came back with a different hand problem.

<img width="2048" height="1905" alt="Three anime illustrations of a lilac-haired tea shop owner with circled close-ups of malformed fingers, a confusing teacup grip, and tangled hands. " src="https://github.com/user-attachments/assets/37500b52-05e5-4a3f-90a5-bd15d0e6a690" />

*We generated Mira’s three original hand problems with Tsubaki.3 in PixAI before making any repairs.*

Next, we repaired each hand three ways: with PixAI’s upgraded Hand Fix tool, with mask-based inpainting in Repaint, and with plain-language editing using the Reference Pro model. We checked how well each one fixed the hand, whether it preserved character details elsewhere, and what it cost in attempts and credits.

We’ll walk through every result below, but if you just want the short answer, here’s what we’d try first to fix AI hands with each type of problem. Hand Fix was the quickest and safest option for malformed fingers. Reference Pro came closest to a natural teacup grip, though we still had to check the rest of the image afterward. And for tangled, overlapping hands, Hand Fix was still our best starting point, though it touched a bit more than the hands.

We ran every test on Nov 10, 2026, using just one character, so your results may differ. This article was written in collaboration with PixAI, and we earn referral credits if you sign up through our invite link. All findings and opinions are our own.

Let’s get those hands fixed!

## How to Fix AI Hands in PixAI: A Beginner Walkthrough

If you’re new to trying to fix AI hands, start with the most obvious mistake in your image. It’s easier to spot what went wrong and see how much the tool changes beyond the hand itself.

We started with the leaf scene. Mira’s raised hand had a thumb attached too high, and one finger was drifting away from the others, making the hand look split down the middle. Before we tried any fixes, we decided what the hand was supposed to look like. Mira should be reaching up to catch the leaf with an open hand, a relaxed thumb, and four fingers.

Here’s what PixAI’s Hand Fix tool generated on the first try:

<img width="2048" height="1603" alt="Before-and-after anime illustrations of a woman reaching for a leaf, with close-ups of a split hand and the repaired five-finger hand. " src="https://github.com/user-attachments/assets/2b727c4b-9197-4235-ad4b-ead534975434" />

*Mira’s Raised Hand Before and After One Pass of Hand Fix in PixAI*

The result looks much better. The hand still reaches toward the leaf, and the thumb and four fingers are now in place. The fingers are slightly long, and the outer one bends out a little sharply, but the hand looks believable overall.

This is local image editing at work. The changes stayed around the hand, and Mira’s face, hair, other hand, and ring looked the same as before.

Here’s how you can make the same repair in PixAI. You don’t need to write a prompt, paint a mask, or adjust any settings. Just follow these steps:

- **Open the editor:** Find your illustration in the Library and click Edit. This opens the Repaint panel, where you’ll find PixAI’s image editing tools.
- **Choose “Fix hands”:** Open the tool menu at the bottom left and select Fix hands. It’s listed alongside Masked Area, Whole Image, and Fix faces.
- **Select the hand:** Draw a box around the hand, leaving a little room around the fingertips. You can add up to 20 boxes, but we selected only Mira’s raised hand.
- **Generate and compare:** Click Generate and wait for the preview. Then drag the slider across the image to compare the original hand with the repaired version.
- **Accept or discard:** Click Accept to keep the new hand, or Discard to drop it. Then use the download option in the toolbar above to save the full-size image.

<img width="2048" height="1015" alt="PixAI Repaint panel with Fix hands selected, a box around a raised hand, and a 4,800-credit Generate button. " src="https://github.com/user-attachments/assets/89a0d332-b2a6-4d3c-89d0-ee19ae03a918" />

*Selecting the Hand to Repair in PixAI’s Hand Fix Tool*

Our repair took one attempt and cost 4,800 credits. This is a limited-time price, as PixAI is currently offering Hand Fix to all users at 40% off its regular 8,000 credits. The downloaded image was also 1232 × 1632, the same size as the original, so the repair didn’t change its resolution.

## Try an AI Hand Fix on Your Own Illustration

The easiest way to try Hand Fix is on an illustration that’s almost perfect except for one bad hand. Before you draw the box, decide what that hand should be doing.

Then keep the box as tight as you can. For one malformed hand, draw the box around just that hand with a little space past the fingertips. If the hand is holding something, include the part of the object the fingers touch. If two hands overlap, put both in one box. A smaller box means less of your image gets redrawn.

That’s all the setup Hand Fix needs. There’s no prompt to write and no mask to paint. Just remember to zoom out and check the whole image once the repair is done.

When you’re ready, [open your illustration in PixAI](https://eap.pixai.art/go/abirami), click Edit, and try Hand Fix. If it’s already in your PixAI Library, you can pick it from there. PixAI’s [Hand Fix guide](https://blog.pixai.art/en/tricky-hands-no-problem-how-to-fix-broken-hands-in-pixai/) covers the tool in more detail if you need help.

Joining PixAI for the first time? Sign up through [our invite link](https://pixai.art/referral?refCode=QCZS8EZS&utm_source=referral&ref_entry=bonus_quest&ref_platform=web&share_copy_id=SC-EN-LINK-T2), generate at least one image, and log in on two separate days. You’ll receive 50,000 bonus credits within 24 hours of completing those steps, and we’ll get the same bonus. Your first repair will use your starting credits, since the bonus arrives later.

Our misplaced thumb was an easy fix, but hands holding objects and overlapping hands are harder to get right. So we put all three of Mira’s hands through the same three repair tools to see how they compared.

## AI Hand Fix vs. Inpainting vs. Reference Editing

Every repair started from the original image, and we kept the first result from each tool, whether it worked or not. If something went wrong, we allowed one more attempt with an adjusted setting, mask, or prompt and recorded what we changed.

Each test includes the prompts, masks, and settings we used, so you can try the same repairs on your own illustrations. We’ll start with the raised hand from our walkthrough, since you’ve already seen how Hand Fix handled it.

### Test 1: Malformed Fingers on a Raised Hand

You might be wondering what we mean by “malformed,” since Mira’s raised hand still looks like a hand at a glance. The problem is that its anatomy doesn’t quite work. The thumb and fingers aren’t connected the way a real hand’s would be. So in this test, a successful fix isn’t about making the hand sharper or cleaner. It’s about making it look natural while keeping the same open, reaching gesture.

This is the leaf scene from our walkthrough. We generated it using [Tsubaki.3](https://docs.pixai.art/docs/models/tsubaki3-prompts) in Pro mode, with a 3:4 aspect ratio and XL resolution (1232 × 1632).

We switched off Quality Tag and Prompt Helper and kept High Priority on, which cost 4,400 credits per image. The hand problem appeared on our second attempt.

Here’s the prompt we used:

```text
Anime illustration, upper body view from the waist up, a young adult woman standing beside a sunlit window inside a glasshouse tea shop, reaching up with her right hand raised in front of her, palm open and fingers relaxed, about to catch a falling green tea leaf, her left hand resting on a wooden counter, gentle curious smile, looking up at the leaf. She has a slender build and natural proportions, short fluffy lilac bob hair, a small sprig of white jasmine tucked behind her left ear, warm brown eyes, light freckles across her nose, a sage-green knit sweater with sleeves ending at the wrists and cream ribbed cuffs, a loose terracotta canvas apron with a small embroidered leaf on the chest, and a thin gold ring with a tiny leaf charm on her right index finger. Hanging plants, glass jars of tea leaves on wooden shelves, warm afternoon sunlight streaming through the glass panes, soft dappled shadows. Clean anime linework, soft cel shading, warm sage, lilac, and terracotta color palette, detailed illustration.
```

We also added a few terms to PixAI’s default negative prompt to make sure the hands stayed visible:

```text
lowres, worst quality, low quality, bad anatomy, explicit, gloves, sleeves covering hands, hands out of frame, cropped hands, text, watermark
```

<img width="2048" height="1516" alt="Four versions of a raised hand, labeled Original, Hand Fix, Repaint, and Reference Pro, with matching close-ups. " src="https://github.com/user-attachments/assets/7f31474a-d7af-4611-87b0-64d79547e67e" />

*The Malformed Hand Repaired With Three Tools*

As we saw earlier, Hand Fix corrected the malformed fingers on the first attempt. We also couldn’t spot any changes outside the selected box.

Next, we tried Repaint, PixAI’s mask-based inpainting tool. You paint over the area you want changed, and Repaint redraws only that part based on your prompt.

We kept its default settings, with Feathering 8, Strength 0.75, and Default mode, and masked the entire hand, part of the wrist, and some empty space around the fingertips. This gave the tool room to redraw the fingers, rather than leaving them restricted to their original positions. We then replaced PixAI’s prefilled prompt with our own:

```text
a natural open hand reaching up toward a falling leaf, palm facing the leaf, one thumb and four relaxed slightly spread fingers, anime illustration, clean lineart, soft cel shading
```

<img width="2048" height="1022" alt="PixAI Repaint editor with a red mask over a raised hand, default settings, and a hand prompt. " src="https://github.com/user-attachments/assets/553380be-7ca9-4f4a-befd-facd03b37812" />

*Our Repaint Inpainting Mask and Prompt for the Malformed Hand in Test 1*

This attempt cost 1,900 credits, and the output was slightly smaller at 1216 × 1632. The linework looked cleaner, and all five fingers were there, but the thumb still sat apart from the rest of the hand, with the same deep gap between them. The falling leaf inside the mask was also redrawn, which wasn’t something we wanted.

Finally, we tried [Reference Pro](https://blog.pixai.art/en/pixai-reference-pro-guide-multi-image-editing-with-natural-language/) (v1.0), PixAI’s natural-language editing model. Instead of drawing a box or painting a mask, you attach your image, along with any reference images, and describe the changes you want in plain language. For this test, we attached only the original image, selected 2K resolution and Auto aspect ratio, and wrote out the fix we wanted:

```text
Edit the attached image. Fix only her raised hand so it becomes a natural open hand reaching up toward the falling leaf, palm facing the leaf, with one thumb and four relaxed, slightly spread fingers. Keep everything else exactly the same, including her face, hair, jasmine flowers, sweater, cuffs, apron, the hand on the counter with its leaf ring, the falling leaf, the window, the background, the lighting, the framing, and the art style.
```

Reference Pro cost 8,000 credits and returned a larger image at 1792 × 2374. This time, the hand had five clear digits and still reached toward the leaf. After scaling the image back down, we found no noticeable changes elsewhere.

For malformed fingers, Hand Fix was the clear winner. It fixed the hand in one pass for 4,800 credits and kept the original image size. Reference Pro also gave us a natural hand, but it cost almost twice as much and returned a larger image. Repaint was the cheapest option, but it didn’t fix the underlying structure and redrew the leaf as well.

### Test 2: A Teacup Grip That Doesn’t Make Sense

Malformed fingers are easy to spot, but an awkward grip can be harder to notice. The hand itself might look fine, yet something feels off about the way it holds an object.

That was the problem with Mira’s teacup. The handle seemed to melt into the top of her index finger, making it difficult to tell how she was holding the cup.

We used the same settings and negative prompt as in Test 1, and this image came out on the first try. We later generated several more scenes with cups, teapots, and whisks, and Tsubaki.3 produced believable grips in almost all of them. This first teacup scene was the clearest miss.

Only the prompt opening changed. Mira’s description, the glasshouse, and the art style stayed the same as in Test 1:

```text
Anime illustration, upper body view from the waist up, a young adult woman standing behind a wooden counter inside a glasshouse tea shop, facing the viewer, holding a small handleless ceramic teacup near her chest with her right hand, fingers wrapped around the cup, steam rising from the tea, her left hand resting on the counter, warm content smile, looking at the viewer.
```

Interestingly, we asked for a handleless cup, but Tsubaki.3 added a handle anyway. That’s where the grip went wrong. We wanted her thumb resting on top of the handle, her index finger hooked through it, and her other fingers curled underneath.

<img width="2048" height="1516" alt="Four versions of a teacup grip, labeled Original, Hand Fix, Repaint, and Reference Pro, with matching close-ups. " src="https://github.com/user-attachments/assets/5f604614-db5c-4cc6-9d0e-947193bf6258" />

*The Teacup Grip Repaired With Three Tools*

For Hand Fix, we drew one box around the hand and handle together because the problem was right where they met. The result made the grip much easier to read. Her thumb rested on top of the handle, and the handle no longer ran into her knuckle.

The changes stayed around the hand and handle, while the cup, steam, and ring looked the same as before. The fingertips underneath the cup were still a little vague, but the hold made sense at a glance.

Next, we tried Repaint with the same default settings as before. We masked the hand, handle, and most of the cup, then used this prompt:

```text
a hand holding a teacup by its handle, thumb resting on top of the handle, index finger hooked through the handle, other fingers curled underneath, anime illustration, clean lineart, soft cel shading
```

The new grip was clear, but it wasn’t the one we asked for. Mira’s fingers wrapped around the body of the cup, while the handle floated above them.

Since the cup and ring were also inside the mask, Repaint changed those too. The beige stoneware cup became white porcelain with a gold rim, and the leaf ring disappeared completely.

For Reference Pro, we included the cup, tea, and ring in the details we wanted to preserve. Those were the elements most likely to change during the edit. Here’s the prompt we used:

```text
Edit the attached image. Fix only the hand holding the teacup so she holds it by the handle, with her thumb resting on top of the handle and her index finger hooked through it, other fingers curled underneath. Keep everything else exactly the same, including her face, hair, jasmine flowers, the cup’s shape and color, the tea and steam, the leaf ring on her finger, her sweater, cuffs, apron, the hand on the counter, the background, the lighting, the framing, and the art style.
```

We kept the same Reference Pro setup as in Test 1, with 2K resolution and Auto aspect ratio. Choosing 4K would have doubled the cost from 8,000 to 16,000 credits.

<img width="2048" height="1035" alt="PixAI Reference Pro with an anime image attached, an edit prompt, 2K resolution, and an 8,000-credit cost. " src="https://github.com/user-attachments/assets/1cec7442-6f8b-45b5-87d1-388c31271c16" />

*The Reference Pro Setup We Used in Every Test*

This time, the result matched our description almost exactly. Mira’s thumb rested on top of the handle, her index finger hooked through it, and her other fingers curled underneath.

The cup kept its original shape and color, the steam stayed in place, and the ring remained on her finger. When we scaled the output back to the original size and compared the two, the only changes we found were around the hand.

For the teacup grip, Reference Pro was the clear winner. It matched the exact hold we described, with the thumb on top of the handle and the index finger hooked through it. Hand Fix made the grip easier to read but didn’t fully match that gesture. Repaint gave us a clear grip, but the handle floated above Mira’s fingers, and the cup and ring changed too because they were inside the mask.

### Test 3: Two Hands Tangled Over a Notebook

Overlapping hands are harder to fix than a single malformed one. Both of Mira’s hands were visible here, but where they crossed, it was hard to tell which fingers belonged to which hand.

Unlike the first two scenes, this one came from a batch of four images, which cost 7,800 credits with the same settings. We picked the image with the most confusing overlap, and again, only the first part of the prompt changed:

```text
Anime illustration, upper body view from the waist up, a young adult woman standing inside a glasshouse tea shop, facing the viewer, holding a small leather recipe notebook against her chest with both hands, her right hand resting over her left hand on the cover, fingers overlapping, both sweater cuffs visible, soft thoughtful smile, looking at the viewer.
```

Our goal was a pose that reads at a glance, with her ringed right hand resting on top of her left and every finger clearly belonging to one hand.

<img width="2048" height="1516" alt="Four versions of two hands on a notebook, labeled Original, Hand Fix, Repaint, and Reference Pro, with matching close-ups. " src="https://github.com/user-attachments/assets/8bf19eb2-da5f-4ce4-b3af-ed4de04667d1" />

*The Overlapping Hands Repaired With Three Tools*

With one box around both hands, Hand Fix improved the layering, and the ringed hand now clearly sat on top. The lower hand showed only its palm and thumb, which is normal since it’s partly hidden underneath. This was also the only test where Hand Fix reached past the hands, slightly redrawing both cuffs and a few edges of the notebook.

Repaint gave us readable hands, but it changed much more than we asked for. Our mask covered both hands and the cuffs, but also the entire notebook, and we used this prompt:

```text
two hands holding a notebook flat against the chest, right hand resting on top of the left hand, each hand with one thumb and four clearly separated fingers, anime illustration, clean lineart, soft cel shading
```

The brown leather notebook with metal rings became a kraft-paper spiral notebook with a green spine, and Mira’s ring was redesigned. In both Test 2 and Test 3, our first masks covered more than the hands, and Repaint redrew everything inside them.

<img width="2048" height="1646" alt="Two PixAI Repaint masks, one covering a hand and teacup and one covering two hands and a notebook. " src="https://github.com/user-attachments/assets/b4128699-dc9c-40df-86e2-b3c8670c6b46" />

*Our First Repaint Masks for Tests 2 and 3*

Reference Pro gave us the cleanest hands of the whole test, with two neatly stacked hands showing four fingers each across the cover. Here’s the prompt:

```text
Edit the attached image. Fix only her two hands so the pose is easy to read: her right hand with the leaf ring rests on top of her left hand, both hands holding the notebook flat against her chest, and every finger clearly belongs to one hand. Keep everything else exactly the same, including her face, hair, jasmine flowers, the brown leather notebook with its metal rings, the leaf ring, her sweater and cream cuffs, apron, the background, the lighting, the framing, and the art style.
```

The rest of the image didn’t hold up as well. The greenhouse roof, plants, shelves, and apron straps were redrawn, and the notebook lost its metal rings despite the prompt. Once we scaled it back down, more than half the image outside the hands had changed.

Mira is still recognizable, but this is no longer the illustration we started with. If we’d judged it by the hand crop alone, it would have looked like our best repair, which is why we always check the full image.

For tangled, overlapping hands, every tool came with a trade-off. Reference Pro gave us the cleanest hands but redrew much of the scene. Hand Fix kept the rest of the image largely intact, though it slightly redrew the cuffs and notebook edges.

## How to Preserve Character Details After an AI Hand Fix

When you fix AI hands, a repair can look perfect in a close-up, but that doesn’t mean the rest of the illustration is unchanged. We saw this in our tests, so we made a point of zooming out and checking the full image after every repair.

Here are six things we looked at before keeping a result:

- **Anatomy and gesture:** Count the fingers, check where the thumb sits, and make sure the hand is still doing what it should. A cleaner-looking hand can still have the wrong number of fingers.
- **Hand-object contact:** If the hand is holding something, check that the grip makes sense. Repaint gave us a clear grip in Test 2, but the handle floated above the fingers.
- **Wrist and clothing boundaries:** Look closely at where the hand meets the sleeve. Even local image editing can affect nearby details, as Hand Fix did with Mira’s sweater cuffs.
- **Character identity and style:** Check the accessories, props, and outfit details that make the character recognizable. Mira’s ring and notebook both changed during our tests.
- **Lighting and shadows:** Make sure the repaired hand matches the lighting on the face and sleeves. A hand with different lighting can stand out even if the anatomy looks right.
- **Final image dimensions:** Check the size of the downloaded file. Our three tools returned different image sizes from the same original, which can affect how sharp a repair looks.

The last point is easy to overlook. Reference Pro returned files about 1.45 times larger than the originals, so its hands looked sharper when placed beside the other results. To compare them fairly, we resized every image to the original dimensions and checked the same area.

<img width="2048" height="1826" alt="Six close-ups of a repaired hand from three tools, shown as downloaded and at a matched scale. " src="https://github.com/user-attachments/assets/2a24b1e3-7188-4ec9-9583-98e95431be72" />

*Comparing the Three Repairs at the Same Scale*

Once all the images were at the same scale, Reference Pro’s hand looked about as detailed as Hand Fix’s. A larger output can make a repair appear sharper than it really is, so resize images to the same dimensions before deciding which tool gave you the better result.

## What to Do When an AI Hand Fix Fails

Not every hand repair works on the first try. Our weakest result came from Repaint in Test 3. The hands themselves came out readable, but the notebook and ring were both replaced. Our mask had covered the whole notebook, so for our one adjusted attempt, we tried a smaller selection.

We went back to the original image and kept the same prompt and default settings. The only thing we changed was the mask. This time, we covered just the two hands and left the notebook’s edges, spine, and metal rings outside the selection.

<img width="2048" height="1008" alt="PixAI Repaint editor with a tight red mask over two hands, leaving the notebook unmasked. " src="https://github.com/user-attachments/assets/c5660c25-2320-4213-bc8e-87dc30b25333" />

*Our Adjusted Repaint Mask, Covering Only the Hands*

The tighter mask helped preserve the notebook. It stayed brown leather, the sweater cuffs were left untouched, and the lower fingers looked cleaner.

The hands still had problems, though. At the top, the two thumbs had no clear base and faded into a blur where the mask ended, leaving a lighter patch on the notebook cover. The leaf ring also disappeared, and an extra pair of metal rings appeared at the bottom of the notebook.

<img width="2048" height="1087" alt="Three close-ups of hands on a notebook, showing the original, a first repair with a replaced notebook, and an adjusted repair with blurred thumbs. " src="https://github.com/user-attachments/assets/b70ecfa5-4519-4195-a696-64e49a49b40c" />

*The Original, Our First Repaint Attempt, and the Adjusted One*

So the second attempt fixed one problem but created new ones. The smaller mask saved the notebook, but its edges left the thumbs looking unfinished. Both Repaint attempts cost 3,800 credits in total.

At this point, we’d stop using Repaint on this image. Another attempt would cost 1,900 more credits, and we’d still be guessing at the right mask shape. Instead, we’d either switch to Hand Fix, which handled this hand better in our tests, or fix the thumbs, add the ring back, and clean up the smudge in a drawing app.

As a general rule, when a repair fails, make one well-reasoned change before trying again. If that doesn’t work, small tweaks to the same approach can burn through credits quickly. Try a different tool, or if only a few small details are left, like a thumb, a ring, or a seam, touch them up by hand.

## Which Tool Should You Use to Fix AI Hands?

Three tools and three tricky hands later, we found that there’s no single best way to fix AI hands. Each tool suited a different kind of correction. The best choice depended on the mistake we wanted to fix and how much of the image we were willing to risk.

Here’s how we’d choose:

- **Hand Fix for a first try:** It needs no prompt or mask, keeps the original size, and changes very little outside the hand. It repaired the malformed fingers, made the teacup grip easier to read, and sorted out the overlapping hands with only small changes to the cuffs and notebook edges.
- **Reference Pro when the gesture needs explaining:** It was the only tool that gave us the exact teacup grip we described. However, it costs the most and enlarges the image. On the hardest pose, it also redrew much of the scene.
- **Repaint for cheap retries:** It’s the lowest-cost option, but anything inside the mask can change. That’s how our cup, notebook, and ring all got redesigned. It works best with a tight mask and some manual touch-up afterward.

Let’s take a look at what each tool got right and wrong in the table below:

<img width="2048" height="1113" alt="Summary table of the best tool, limits, attempts, credits, and side effects for three hand problems, beside Mira holding a teacup. " src="https://github.com/user-attachments/assets/a936bfae-73d8-4855-b707-eebf1ef1d746" />

*How the Three Tools Handled Each Hand Problem in Our Tests*

If you only take one thing from our tests, start with Hand Fix for most hand problems, especially while its temporary 40% discount lasts. Choose Reference Pro when you need a specific grip or pose, but check the full image afterward. Repaint is the cheaper option when you want to try different corrections and can keep the mask tight.

Running all three tools on every hand, including our one retry, cost us 46,000 credits at November 2026 prices. But you won’t need to spend that much on every correction.

Fixing Mira’s malformed fingers in Test 1 took just one Hand Fix pass, which cost 4,800 credits with the discount (8,000 at the regular price). If you have an illustration that’s perfect apart from one hand, try [Hand Fix in PixAI](https://eap.pixai.art/go/abirami) and see how far it gets you.

## FAQs About How to Fix AI Hands

Wondering how these tools would handle your own illustrations? Here are answers to some common questions about fixing hands in AI art, based on our tests:

- **Can an automatic hand fixer correct extra fingers?** It can repair badly formed fingers without a prompt or mask, making it a good first try. Hand Fix rebuilt Mira’s split hand on the first pass, though none of our images had a clear extra finger to test.
- **What should I include in an inpainting prompt for a hand?** Describe what the hand is doing, rather than just how it should look. Mention the gesture, where the thumb sits, and how the fingers hold an object. Leave a little room around the hand when creating your mask.
- **Why does fixing a hand change the sleeve or object?** Most tools can redraw anything inside the selected area, including cuffs, cups, and props. Keep your mask or box tight. With Reference Pro, also mention the nearby details you want to preserve.
- **Can upscaling fix incorrect hand anatomy?** No. Upscaling makes the image larger, but the hand keeps the same anatomical errors. Fix the fingers first, then upscale if you need a bigger file.
