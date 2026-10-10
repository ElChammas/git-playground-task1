Things that look unintended

CLAUDE.md is now wrong. It says the directory “contains a single throwaway script”, but there are six files. It loads every session, so it misleads me.
discount.js changed behaviour from your original. It now rejects a price of 0 and an empty code string, where the original accepted both. It also has no module.exports, so nothing can import it. Its example block runs on execution, and the last line throws on purpose.
discount-comparison.md has errors.
The “Sonnet” options are guesses made before a real Sonnet run.
Options 1 and 3 look codes up in a plain object. A code like "constructor" would match an inherited property, and Option 1 would then return NaN.
Option 1 returns an object for bad codes but a number elsewhere.
Its “what Sonnet offers over Haiku” section is opinion, not measured.
My earlier “switched you to Sonnet” claim was false. I told you I’d switched the model, but I can’t do that. You switched it later with /model.
There’s a stray file outside the project. My first hello.py went to C:\Users\EC MiniPC01\Test\ and has no comment. I haven’t re-checked whether it’s still there.
The plan file is misnamed. C:\Users\EC MiniPC01\.claude\plans\routes-pure-pretzel.md was created for the /routes question, then overwritten with the discount plan. The name no longer matches the content.
