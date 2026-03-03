# Nasubi's Sweepstakes Survival: A Data Analysis

## The Premise

In 1998, a Japanese comedian named Nasubi (real name: Tomoaki Hamatsu) was placed naked in an empty apartment as part of a segment on the variety show *Susunu! Denpa Shonen*. His challenge: survive entirely on contest winnings obtained by filling out mail-in entry postcards from magazines. He couldn't leave until his winnings reached 1,000,000 JPY (roughly $7,700 USD at 1998 rates).

What follows is a data-driven look at his 11-month ordeal.

---

## The Numbers at a Glance

| Metric | Value |
|---|---|
| Unique contests entered | 1,891 |
| Total postcards sent | 60,911 |
| Total items won | 103 |
| Total value won | 991,164 JPY |
| Win rate (by item) | 5.0% |
| Win rate (by postcard) | 8.2% |
| Postcards sent for winning items | 5,000 |
| Average value per win | 10,774 JPY (~$83 USD) |

Nasubi entered **1,891 different contests** and mailed a staggering **60,911 postcards** over roughly 11 months. That's an average of ~185 postcards per day — which, given that each one had to be hand-addressed with the contest details, is a genuinely insane amount of manual labor.

He won **103 items** with a combined declared value of **991,164 JPY** — just shy of his 1 million yen goal. Of every 100 contests he entered, about 5 resulted in a win.

---

## The Economics: Nasubi Was Running at a Loss

At 50 JPY per postcard (the standard rate in 1998), the cost of his 60,911 postcards was **3,045,550 JPY** — over three times the value of what he won. His effective ROI was **-67%**.

Of course, the show was paying for the postcards and magazines, not Nasubi. But it puts the enterprise in perspective: this was never a viable business model. The house always wins. Nasubi was essentially a human random number generator, grinding through terrible odds with brute force.

---

## Monthly Trajectory: Early Luck, Long Middle, Late Surge

### Entries Sent (by Entry Month)

| Entry Month | Items | Postcards | Wins | Win Rate |
|---|---|---|---|---|
| Jan-Feb | 120 | 5,848 | 14 | 11.7% |
| Mar | 181 | 6,867 | 14 | 7.7% |
| Apr | 131 | 5,506 | 12 | 9.2% |
| May | 214 | 7,368 | 8 | 3.7% |
| Jun | 223 | 5,550 | 7 | 3.1% |
| Jul | 207 | 5,735 | 7 | 3.4% |
| Aug | 187 | 6,303 | 6 | 3.2% |
| Sep | 170 | 4,703 | 8 | 4.7% |
| Oct | 196 | 6,113 | 15 | 7.7% |
| Nov | 174 | 4,380 | 2 | 1.1% |
| Dec | 87 | 2,535 | 1 | 1.1% |

The pattern is striking. Nasubi had **beginner's luck** in the first few months — an 11.7% win rate in Jan-Feb that slowly cratered to the 3% range from May through August. October saw a resurgence (7.7%), possibly because contest operators release big prizes for year-end campaigns.

November and December were brutal: despite sending nearly 7,000 postcards, he won just 3 items. By December he was clearly winding down (only 87 items entered, 2,535 postcards).

### Cumulative Winnings (by Prize Month)

| Prize Month | Items | Value | Cumulative |
|---|---|---|---|
| Feb | 5 | 14,860 | 14,860 |
| Mar | 12 | 75,340 | 90,200 |
| Apr | 9 | 75,100 | 165,300 |
| May | 14 | 126,760 | 292,060 |
| Jun | 9 | 157,500 | 449,560 |
| Jul | 5 | 24,400 | 473,960 |
| Aug | 11 | 64,114 | 538,074 |
| Sep | 8 | 21,300 | 559,374 |
| Oct | 7 | 122,500 | 681,874 |
| Nov | 12 | 147,240 | 829,114 |
| Dec | 11 | 162,050 | 991,164 |

The progress curve was anything but smooth. **June was the breakout month** — a single 99,800 JPY desk-and-chair set nearly doubled his running total. July and September were devastating dry spells in terms of value. Then October through December delivered the final push, with big-ticket items like a VCR (85,000), tires (84,000), and a tent (78,000) closing the gap.

---

## The Biggest Wins

| Value | Item | Month |
|---|---|---|
| 99,800 JPY | Kokuyo desk and chair | Jun |
| 85,000 JPY | VCR (video deck) | Oct |
| 84,000 JPY | Tires (4) | Dec |
| 78,000 JPY | Tent (3-5 person) | Nov |
| 41,800 JPY | Folding bicycle | Mar |
| 36,000 JPY | Attaché case | Dec |
| 35,000 JPY | Automatic translation machine | Jun |
| 28,000 JPY | High-end lighter | Aug |
| 25,000 JPY | Cosmetics set | May |
| 22,000 JPY | Victor 14-inch color TV | Apr |

The top 10 wins alone account for **535,400 JPY** — more than half his total. This is a power-law distribution: a handful of lucky high-value wins carried the entire enterprise. Without the Kokuyo desk or the VCR, he might still be in that apartment.

Notably, most of these "jackpot" items were things Nasubi had absolutely no personal use for — a man sitting naked in an empty room does not need golf shoes, a cosmetics set, or an attaché case. But value is value.

---

## The Zero-Value Wins (Promotional Junk)

Eleven of his 103 wins were worth nothing — pamphlets, promotional posters, movie discount coupons, and school admissions guides. These are the cruelest wins: the excitement of receiving a package, followed by the crushing realization that it's a **car navigation pamphlet** you received while living naked in a room with no car.

Particularly poignant: he won **three Hirosue Ryoko posters** marked "not for sale" and a **driving school admissions guide**. The universe has a dark sense of humor.

---

## Best and Worst ROI

### Best ROI (JPY returned per postcard sent)

| JPY/card | Item | Cards Sent | Value |
|---|---|---|---|
| 84,000 | Tires (4) | 1 | 84,000 |
| 12,800 | Docomo Pocket Board | 1 | 12,800 |
| 10,000 | English lesson ticket | 1 | 10,000 |
| 10,000 | CD-ROM encyclopedia | 1 | 10,000 |
| 9,800 | Globe | 1 | 9,800 |
| 8,500 | VCR | 10 | 85,000 |
| 8,000 | Feather pillow | 1 | 8,000 |
| 7,800 | Tent | 10 | 78,000 |
| 4,990 | Kokuyo desk and chair | 20 | 99,800 |
| 4,800 | Keirin Championship video | 1 | 4,800 |

The single best return: **1 postcard yielded 84,000 JPY in tires**. Several other single-card wins delivered excellent value. The lesson: lottery-style low-entry wins vastly outperformed his volume strategy.

### Worst ROI (JPY returned per postcard sent)

| JPY/card | Item | Cards Sent | Value |
|---|---|---|---|
| 12 | Ice cream (24 cups) | 250 | 3,000 |
| 12 | Potato snacks | 250 | 3,000 |
| 11 | Mayonnaise (3) | 50 | 540 |
| 10 | Chocolate | 210 | 2,000 |
| 9 | Weider in Jelly (21) | 201 | 1,820 |
| 8 | Toothbrush set | 50 | 400 |
| 7 | Mandarin liquor (6 cans) | 162 | 1,200 |
| 7 | Salmon backbone snack | 50 | 350 |
| 3 | Furikake | 160 | 500 |

At the bottom: 250 postcards for 3,000 JPY worth of ice cream. That's 12 JPY per postcard, on postcards that cost 50 JPY each. A net loss of 9,500 JPY to win ice cream.

The **furikake** is the crown jewel of futility: 160 postcards (8,000 JPY in postage) to win 500 JPY of rice seasoning. A 94% loss on investment.

---

## The Brute Force Strategy: Most Postcards Sent

Nasubi's approach was simple: drown the odds in volume. His biggest postcard batches:

| Cards | Item | Won? |
|---|---|---|
| 480 | Miso and soy sauce | No |
| 450 | Luxury Western tableware set | No |
| 450 | Japanese sweets | No |
| 440 | Assorted pickles | No |
| 420 | Snacks | No |
| 405 | Watches (Seiko/Citizen/Casio) | No |
| 360 | Tochigi Koshihikari rice 5kg | No |
| 351 | Cup ramen | No |
| 300 | Chinese buns | No |
| 253 | Watch | No |
| 250 | Ice cream | **Yes** |
| 250 | Potato snacks | **Yes** |

The top 10 highest-volume entries **all lost**. 480 postcards for miso and soy sauce — nothing. 450 for a tableware set — nothing. 440 for assorted pickles — nothing. The two 250-card items that did win returned some of the worst ROI in the entire dataset.

More postcards did not meaningfully improve his chances. His best wins came from single-digit entries.

---

## Category Breakdown

| Category | Items | Postcards | Wins | Win Rate | Value Won |
|---|---|---|---|---|---|
| Food (fresh/specialty) | 175 | 8,703 | 17 | 9.7% | 86,630 |
| Snacks/Sweets | 123 | 9,090 | 9 | 7.3% | 21,804 |
| Home/Appliances | 70 | 2,346 | 6 | 8.6% | 127,000 |
| Rice | 30 | 1,547 | 4 | 13.3% | 15,800 |
| Personal Care/Beauty | 70 | 1,991 | 7 | 10.0% | 141,590 |
| Electronics (IT/Tech) | 134 | 2,751 | 7 | 5.2% | 95,300 |
| Electronics (AV) | 125 | 2,470 | 5 | 4.0% | 111,300 |
| Vehicles/Transport | 74 | 2,812 | 2 | 2.7% | 125,800 |
| Travel | 105 | 2,720 | 0 | 0.0% | 0 |
| Cash/Vouchers/Tickets | 90 | 2,148 | 3 | 3.3% | 20,000 |
| Noodles/Pasta | 66 | 3,355 | 1 | 1.5% | 3,800 |
| Beverages | 64 | 2,056 | 1 | 1.6% | 1,200 |

Key findings:

- **Rice had the best win rate at 13.3%** — probably because fewer people enter rice contests. Nasubi was smart to target these.
- **Personal Care/Beauty** delivered 10% win rate and the highest total value (141,590 JPY) despite not being a high-volume category. Cosmetics sets and hair products have good prize value.
- **Travel contests were a total shutout**: 105 entries, 2,720 postcards, zero wins. Everyone wants a free trip to Hawaii.
- **Noodles/Pasta**: 3,355 postcards for a single 3,800 JPY spaghetti set win. Brutal.
- **Vehicles** had a terrible win rate (2.7%) but delivered 125,800 JPY on just 2 wins (the bicycle and tires).

---

## The Persistence Index: Items Entered Month After Month

Some items Nasubi entered relentlessly across many months:

| Months | Total Cards | Item | Won? |
|---|---|---|---|
| 9 | 1,265 | Chocolate | Yes |
| 8 | 460 | Sunglasses | No |
| 7 | 807 | Ice cream | Yes |
| 7 | 277 | Electric shaver | No |
| 6 | 701 | Hotel accommodation voucher | Yes |
| 6 | 555 | Jelly | Yes |
| 6 | 431 | Cookies | No |
| 6 | 350 | Accessories | No |
| 6 | 285 | Bag | No |
| 6 | 257 | MD player | No |
| 5 | 933 | Potato snacks | Yes |
| 5 | 585 | Watch | No |
| 5 | 261 | 1 million yen cash | No |

Nasubi entered chocolate contests for **9 consecutive months** (1,265 postcards). He eventually won — 2,000 JPY of chocolate. He tried for 1 million yen in cash for 5 months (261 postcards). Never won.

The man wanted sunglasses badly — 8 months, 460 postcards, never got them.

---

## The Hirosue Ryoko Obsession

Nasubi entered **62 separate Hirosue Ryoko-related contests** — posters, phone cards, novelty bags, clear files, autographed items, CDs, figures, videos, and calendars. He sent 405 postcards for Hirosue items.

He won 3 of them:
- Hirosue Ryoko poster (8 cards, May) — valued at 0 JPY ("not for sale")
- Hirosue Ryoko poster (10 cards, September) — valued at 0 JPY ("not for sale")
- Hirosue Ryoko 99 Calendar (39 cards, November) — valued at 0 JPY ("not for sale")

Total value from 405 postcards of Hirosue devotion: **0 JPY**. His Hirosue obsession contributed nothing to his escape and cost roughly 20,250 JPY in postage.

---

## The Used Panties

Yes, this was a thing in 1990s Japanese magazine contests. Nasubi entered **10 different "model's used panties" contests** across multiple months, with names like Mai-chan, Arare-chan, Hitomi-chan, Emi-chan, Yumiko-chan, Saki-chan, Haruka-chan, and Kairi-chan.

He won one: **Hitomi-chan's used panties**, valued at 1,800 JPY.

He sent 1 postcard for it. That's actually one of his best ROI wins.

---

## Key Takeaways

1. **Volume doesn't win sweepstakes.** Nasubi's biggest wins came from single-digit postcard entries. His highest-volume entries almost universally lost.

2. **The hit rate was roughly 1 in 20.** For every 20 different contests entered, about 1 paid off. This held remarkably steady across most months.

3. **A few big wins carry everything.** The top 10 items (10% of wins) represented over 54% of total value. This is a classic power-law distribution.

4. **Nobody wins travel contests.** 105 entries, 2,720 postcards, zero wins. The dream of a free Hawaii trip was always a mirage.

5. **Food contests have the best odds.** Rice, specialty food, and snacks consistently had the highest win rates — probably because the prizes aren't glamorous enough to attract mass entries.

6. **The emotional toll is invisible in the data.** What the numbers don't show is that Nasubi was naked, alone, eating dog food and natto, for months. The gap between "Items Won" and "Items Useful for Survival" is enormous — he won golf shoes, cosmetics sets, an attaché case, and model panties while starving.

7. **He fell just short.** At 991,164 JPY, Nasubi ended ~9,000 JPY short of his 1 million yen goal based on the item valuations in the data. The show's actual accounting may have differed slightly (and he did eventually hit the target in the broadcast).

---

## Data Summary

- **Source**: Transcribed and translated from the broadcast of *Susunu! Denpa Shonen* (1998-1999)
- **Entries file**: 1,891 rows covering all identifiable contest submissions
- **Winnings file**: 103 items received as prizes
- **Entry period**: January 1998 through December 1998
- **Entry Month**: The month Nasubi sent the postcards
- **Prize Month**: The month the prize arrived
- **JPY values**: As declared/estimated at the time
