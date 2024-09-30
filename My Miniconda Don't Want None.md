# How to Set Up Miniconda on Ubuntu (Installed via Deskify on Your Android Tablet)

So, you've got this badass Ubuntu thing going on your tablet. Good shit. Now let’s set up Miniconda so you can actually *do* stuff. It’s gonna be awesome. Trust me.

## 1. **Update Your System**

Alright, first thing you gotta do, update your fukn system, bro. Don’t wanna be working with some outdated bullshit. Open that terminal and type this magic:

```bash
sudo apt update && sudo apt upgrade
```

This is like... cleaning your room before getting productive. You know? Gotta start fresh.

## 2. **Install Required Packages**

Alright, listen, you need some tools here, okay? Nothing fancy, just basic sh*t like `wget` and `bzip2`. So just... *fukn* install them with this:

```bash
sudo apt install wget bzip2
```

Easy peasy. Just let it do its thing. Don’t overthink it.

## 3. **Download Miniconda**

Now, okay, we’re getting somewhere. Time to download Miniconda. It’s like the foundation for all the cool shit we’re gonna do. If you're on a 64-bit system, grab the script with:

```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```

Wait... wait for it. Don’t get impatient.

## 4. **Run the Installer**

Okay, now, we’re in the *zone.* Time to install this bad boy. Don’t freak out, just run this:

```bash
bash Miniconda3-latest-Linux-x86_64.sh
```

Follow the prompts. I mean, it’s not rocket science. Just hit “yes” to whatever looks like a good idea, alright? 

## 5. **Initialize Conda**

Okay, now we’re really getting shit done. You need to tell your shell that Conda exists, so it can do the magic. Run:

```bash
~/miniconda3/bin/conda init
```

Restart your terminal or just type:

```bash
source ~/.bashrc
```

At this point, you might feel like a hacker, and that’s good. Own it.

## 6. **Create a Conda Environment**

Alright, here we go. Time to *make* an environment. Like, this is where your Python magic happens. We’re going with Python 3.10 because... why not, right?

```bash
conda create --name myenv python=3.10
```

Then, fukn *activate* it:

```bash
conda activate myenv
```

BOOM. You’re in. Now you’ve got this whole environment dedicated to... whatever the fuk you want to code. You’re unstoppable now.

## 7. **Install Necessary Packages**

Alright, focus up, 'cause now we’re getting to the important part: installing the packages you need. Like, I dunno, **numpy** and **pandas**—everybody uses that shit. So let’s install it:

```bash
conda install numpy pandas
```

Okay, okay, *woah*. Look at you go. You're basically running a whole fukn data science lab on your tablet now. Congrats, buddy.

## And That’s It! 🎉

Dude, you're done. You’ve got this fukn beautiful Miniconda setup, and now you can get down to some serious Python stuff. Or take a break. You deserve it. But seriously, good job, bro. You *crushed* it.

---

Hit me up if you run into any fukn snags, with these instructions, I dunno wtf is real anymore 

Now... time to hak t3h planet

l0lrsk8zzzzz l88888z

~nix