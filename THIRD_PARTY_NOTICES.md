# Third-party data notices

## Korean word list

The word list in `dist/words.js` is derived from the `kr_korean` headword and part-of-speech data bundled with the earlier Kingle project. The original file has no version or license metadata. Its filename and two-column format match the public [`korean-word-game/db`](https://github.com/korean-word-game/db) dataset, which says it extracted headwords from the National Institute of Korean Language's *Standard Korean Dictionary* on 2018-11-13. The exact upstream revision of the bundled file could not be independently confirmed.

This game filters the list to two- and three-syllable entries, recovers selected hyphenated noun entries, and adds game-specific everyday words and a curated selection of familiar product and brand names. The product and brand list is not exhaustive; trademarks remain with their respective owners. The dictionary contains headwords only; definitions, quotations, pronunciation and multimedia are not included.

Product spellings were cross-checked against official product catalogs from [Binggrae](https://www.bing.co.kr/product/detail?PDT=6), [Nongshim](https://brand.nongshim.com/all_product/index), [Orion](https://www.orionworld.com/goods/list/27?category=0102), and [Lotte Wellfood](https://www.lottewellfood.com/).

The National Institute of Korean Language states that Standard Korean Dictionary and Urimalsaem material without a separate notice is distributed under the [Creative Commons Attribution-ShareAlike 2.0 Korea license (CC BY-SA 2.0 KR)](https://creativecommons.org/licenses/by-sa/2.0/kr/). The upstream dataset project states that its collected headword and part-of-speech list has no copyright and may be redistributed. To preserve attribution and share-alike terms conservatively, the modified word-list data in this project is provided under CC BY-SA 2.0 KR.

Attribution: “Based on headword data from the National Institute of Korean Language's *Standard Korean Dictionary*, via [`korean-word-game/db`](https://github.com/korean-word-game/db); filtered and supplemented for KINGLE ROGUE.”

This notice applies to the dictionary data only. It does not grant a license to the game's code or artwork.
