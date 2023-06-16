<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

E taunaki ana kia whakauruhia nga nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) i te tuatahi, katahi ka `direnv allow` i muri i te whakaurunga ki te raarangi (ka mahia aunoatia [te .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) i muri i te urunga ki te raarangi).

Ko te tikanga: ko te whakamaoritanga Hainamana ki te reo Hapanihi, Korea, Ingarihi, Ingarihi ki etahi atu reo katoa. Mena kei te pirangi koe ki te tautoko i te Hainamana me te reo Ingarihi, ka taea e koe te tuhi `zh: en` .

Ko te tikanga: ko te whakamaoritanga Hainamana ki te reo Hapanihi, Korea, Ingarihi, Ingarihi ki etahi atu reo katoa. Mena kei te pirangi koe ki te tautoko i te Hainamana me te reo Ingarihi, ka taea e koe te tuhi `zh: en` .

* [waehere mua-mutunga](https://github.com/xxai-art/web)
* [Ngā mōkihi reo mō te pae whānui](https://github.com/xxai-art/web/tree/main/i18n)
* [Mōkihi reo mō ngā kōwae takiuru](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Paetukutuku Tuhituhi Reo-maha](https://github.com/xxai-doc)

Ko te reo hotaka o mua ko [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , e taapiri ana i etahi ahuatanga i runga i te wetereo coffeescript, tirohia [./coffee_plus.md](./coffee_plus.md) .

## Te whakawhanaungatanga o nga paetukutuku me nga tuhinga

Hanga i runga i nga kaupapa e 3 e whai ake nei

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Ko te kumara ko `.mdt` , ka taea e koe te whakamahi i te wetereo rite ki `<+ ./coffee_plus/import.js>` ki te titiro ki nga konae o waho, me te whakaputa tohu ki te `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Ko te whakamaoritanga Markdown e kore e whakamaori i nga waehere me nga hononga, ka huna hoki i nga rerenga whakamaoritanga. Mena ka whakarereketia te whakamaoritanga engari kaore i whakarereketia te tuhinga taketake, ka mahia ano e kore e tuhirua te whakarereketanga o te whakamaoritanga.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Ko nga konae reo hei whakamaori i nga paetukutuku i hangaia e `yaml` .

### Nga Tohutohu Whakamaoritanga Tuhinga

Tirohia te kohinga waehere [xxai-art/doc](https://github.com/xxai-art/doc)

E taunaki ana kia whakauruhia nga nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) i te tuatahi, katahi ka `direnv allow` i muri i te whakaurunga ki te raarangi (ka mahia aunoatia [te .envrc](https://github.com/xxai-art/doc/blob/main/.envrc) i muri i te urunga ki te raarangi).

Hei karo i te turanga waehere nui kua whakamaoritia ki nga rau reo, i hanga e ahau he turanga waehere motuhake mo ia reo me te hanga whakahaere hei penapena i te turanga waehere

Ko te tautuhi i te taurangi taiao `GITHUB_ACCESS_TOKEN` me te whakahaere i [te create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) ka hanga aunoa i te putunga waehere.

Ko te tikanga, ka taea hoki e koe te whakauru ki roto i te turanga waehere.

Tohutoro tuhinga whakamaori [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Ka whakamaoritia te waehere tuhinga e whai ake nei:

Ko [te bunx](https://bun.sh/docs/cli/bunx) he whakakapinga mo te npx, he tere ake. Ae ra, ki te kore koe e whakauru i te bun, ka taea e koe te whakamahi i `npx` .

`bunx mdt zh` ka huri i `.mdt` ki te raarangi zh hei `.md` , tirohia nga konae hono e 2 kei raro

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

Ko `bunx i18n` te waehere matua mo te whakamaoritanga (mehemea kua whakauruhia e koe `nodejs` , engari kaore i te whakauruhia `bun` me `direnv` , ka taea hoki e koe te whakahaere i `npx i18n` hei whakamaori).

Ka poroporoaki [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) , ko te whirihoranga o `i18n.yml` i roto i tenei tuhinga e whai ake nei:

```
en:
zh: ja ko en
```

Ko te tikanga: ko te whakamaoritanga Hainamana ki te reo Hapanihi, Korea, Ingarihi, Ingarihi ki etahi atu reo katoa. Mena kei te pirangi koe ki te tautoko i te Hainamana me te reo Ingarihi, ka taea e koe te tuhi `zh: en` .

Ko te mea whakamutunga ko [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , e tango ana i nga korero i waenga i te taitara matua me te taitara hauraro tuatahi o `README.md` o ia reo hei whakaputa i te urunga `README.md` . He tino ngawari te waehere, ka taea e koe te titiro ki a koe ano.

Ka whakamahia te API Google mo te whakamaori kore utu. Mena kaore e taea e koe te uru atu ki a Google, whirihora me te whakarite takawaenga, penei:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Ka whakaputahia e te tuhinga whakamaori he keteroki kua whakamaoritia i roto i te whaiaronga `.i18n` , tena koa tirohia me `git status` ka taapiri atu ki te putunga waehere hei karo i nga whakamaoritanga.

Whakahaerehia `bunx i18n` i nga wa katoa ka whakarereke koe i te whakamaoritanga hei whakahou i te keteroki.

Mena ka whakarerekehia te tuhinga taketake me te whakamaoritanga i te wa kotahi, ka raruraru te keteroki, na, ki te hiahia koe ki te whakarereke, ka taea e koe anake te whakarereke i tetahi, katahi ka whakahaere i `bunx i18n` ki te whakahou i te keteroki.
