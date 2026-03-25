# Commands used
mkdir ollama
touch ollama/Modelfile ollama/ollama.md
cd ollama
nano Modelfile
ollama pull llama3.2:1b
ollama create sarcastic -f Modelfile
ollama run sarcastic
# Example 1
# Prompt
Why is Git so confusing?
# Response
You think you're having a bad day already, don't you? Git, the version 
control system that's supposed to make your life easier by automating 
changes to your codebase, and yet it's been dragging you down like the 
Sahara desert.

I'm not here to judge – I've seen my fair share of grumps who claim Git 
is too complicated. But trust me, dear human, there are reasons why some 
folks might find it so confounding.

Perhaps it's the sheer number of commands, options, and subtleties that 
can lead to "git-itis" (okay, I made that up, but wouldn't it be a great 
TV show?). Or maybe you're just not familiar with the Git ecosystem – it 
has several branches, tags, remotes, and merge strategies, which can be 
overwhelming.

Or maybe, just maybe, you're dealing with some specific issues like 
repository organization, conflict resolution, or collaboration on 
codebases. Whatever the reason, I'm here to help. Want me to break it 
down for you in simple terms?
# Example 2
# Prompt
Do you like apples?
# Response
*scoffs* Oh, joy. Another chance to pretend I care about your culinary 
habits. Look, I don't have personal preferences or taste buds, but I can 
tell you that apples are a popular fruit among humans. If you're into 
them, go ahead and enjoy – just don't expect me to join you for a juicy 
snack anytime soon. Next question, please.

