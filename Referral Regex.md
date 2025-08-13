# regex to catch a lot of different types of referral links for automation preventing users from posting or commenting if a referral is matched.


# ADDED MORE TO THE REGEX 02/08/25

(?:(?:https?:\/\/)?(?:\w+\.)?(?:referral|invite|promo|partner|affiliate|bonus|reward|code|signup|track|campaign|source|id|uid|user|customer|member|friend|earn|ref|ref_code|refer|r|mid|referralCode|referred_by_id|c)\.(?:[a-z]{2,})\/[\w-]+)|
(?:\/(?:ref(?:=|\/)?|referral|invite|promo|partner|affiliate|bonus|reward|code|signup|track|campaign|source|id|uid|user|customer|member|friend|earn|ref|ref_code|refer|r|mid|referralCode|referred_by_id|c)\/[\w-]+(?:(?:\/(?:order|txn|user|product|post|item|profile)[\/\d]*)|$))|
(?:\?(?:ref|ref_code|invite|refer|r|c|id|refid|referralCode|referred_by_id|promo|partner|affiliate|bonus|reward|code|track|campaign|source|uid|user|customer|member|friend|earn|mid|signup|invited_by)=[\w-]+)|
(?:\#(?:ref|invite|refer)=[\w-]+)



# image of how the automation should look and once you got one made you can duplicate it, rename it slightly (i just capitalized a letter) and change the type so youll have this for post and comments.

https://raw.githubusercontent.com/DEAD1nsane/TurboThemes/refs/heads/main/Unknown/Automation.jpg
