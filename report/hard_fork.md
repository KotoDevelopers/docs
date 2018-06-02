
# ハードフォーク　FAQ(Hard fork FAQ)


### 私が保有するKotoは無くなりますか？(Will I lose my Koto I already have?)
> 無くなりません。ハードフォークに対応した新しいウォレットを事前に配布しますので、そちらで起動をすると、決定したブロック高で同額の新Kotoが保有されます。チェーンが引き継がれる訳です。

> It will not disappear. We will distribute a new wallet corresponding to the hard fork in advance so if you start with it, you will have the same amount of new Koto at the block height you decided. The chain is taken over.

### XXXというウォレットを使っています、どうなりますか？(I am using a wallet called XXX, what happens?)
> サードパティーのウォレットはそれぞれの開発者にお問い合わせください  

> For third-party wallets, please contact the respective developers

### 旧Koto（分岐した旧チェーン）はどうなりますか？(What happens to the former Koto (branched old chain)?)
> マイニングが行われないチェーン、及びコインは資産価値を持ちません。運営チームは旧Kotoへの一切のメンテナンスを行いませんので、マイナーが消滅した時点で旧Kotoの価値は消滅します。なお、koto.cashさんが戻ってきて旧Kotoのメンテナンスをする可能性は否定できません。  

> Chains that are not mined, and coins do not have asset value. Since the management team will not do any maintenance to former Koto, the value of old Koto disappears when the minor disappears. You can not deny the possibility that koto.cash will come back and do maintenance of old Koto.  

### 結局GPU耐性付けないのですか？(Does not end up GPU tolerance after all?)
> CPU優位なアルゴリズムを採用した場合、CPU優位にすればするほど、スペックの低いCPUによるマイニングは困難になる問題を抱えています。また、GPUが参入することでハッシュレートが高まり、セキュリティが向上するという利点もあります。GPUを根絶する程のアルゴリズムを採用していないことから、GPUマイナーにもKotoのホルダーとして権利があります。コミュニティの投票も考慮した結果、アルゴリズムは変更しないことになりました。  

> When adopting a CPU-dominant algorithm, the more CPU dominant, the more difficult it is to mining with CPUs with low specifications. In addition, the entry of the GPU increases the hash rate, which also has the advantage of improving security. As GPU minor does not adopt algorithm to eradicate GPU, it has right as a holder of Koto. As a result of considering the voting of the community, we decided not to change the algorithm.  

### 開発者報酬はどんなもので、どういう用途ですか？(What is the Sustainability fund and what is it used for?)
> 開発メンバーには自身の努力に対する報酬が必要です。そうしなければ、タダ働きに抵抗感のある開発メンバーから順次チームを離れ、チームの開発能力は低下します。そのためコミュニティと協議し、半減期までという条件で、また収支の概要を報告をするという条件で、次の用途での開発者報酬を得ることが許可されました。  
> 収支報告は（総額ーPR費ー開発費＝残額など）という形でおおよそを想定しています。  

> Development members need to pay for their own efforts. Otherwise, teams will leave the team in turn from developing members who are resistant to working without lowering team development capabilities. Therefore, in consultation with the community, it was permitted to obtain Sustainability fund for the following use on condition that it reports half of the expiration date and summary of income and expenditure.  
> The income and expenditure report is assumed to be roughly in the form of (total amount - PR expenses - development expenses = remaining amount etc).  


> A：運営メンバーへの報酬支払い  
> 運営メンバーへの報酬へ支払います。比率や人事制度などはチーム内で協議し、収入内でやりくりすることを約束致しました。報酬が不足した場合も、半減期前に再度ハードフォークを行うことはありません。  
> B：運営が依頼した開発業務などへの報酬  
> 立場を悪用した強引な開発ができないよう、運営チームが強大になりすぎることを危惧しています。そのためKotoの為に必要と思われるサービス開発に対してバウンティを設定し、リリース、運用してくれた人に対して報酬を支払おうと思います。  

> Payment of remuneration to operating members  
> We will pay to the members for remuneration. We promised to discuss proportions and personnel systems etc. within the team and to make ends meet within the income. Even if the reward is insufficient, we will never do hard fork again before half-life.  
> Remuneration for development work etc. that management requested  
> I am worried that the management team will be overwhelming so that I can not forcefully exploit my position. Therefore, I will set a bounty for service development which is considered necessary for Koto, I will pay compensation for those who released and operated.  

### なぜKotoという名前を引き継ぐのですか？(Why will you continue to use the name Koto?)
> 今のKotoには独自性あるサービスやブロックチェーンの活用事例はありません。にもかかわらず、ここまで国内外から多くのユーザを惹きつける理由は名称と、そのロゴにもあります。そのためKotoという名称を引き継ぎ、同時にロゴも引き継ぎました。  

> Currently Koto has no case of using unique services or block chains. Nonetheless, the reason for attracting many users from home and abroad is the name and its logo. For that reason I took over the name Koto and also took over the logo at the same time.  

### プールは新Kotoに切り替わりますか？(Does the pool switch to the new Koto?)
> プールも特定のブロック高で新Kotoになるようアナウンス致します。  

> The pool will also announce to be a new Koto at a specific block height.  

### ハードフォークの時KotoBOTの中身はどうなりますか？(When thehard fork takes place, what happens to the contents of KotoBOT?)
> Discord内のKotoBOT開発者はLimitですが、念のため中身を引き出すことをお勧めします。  

> Although KotoBOT developer in Discord is Limit, we recommend that you draw out the contents as a precaution.  

> 具体例  
> HF後にnewSwingを立ち上げた場合、oldSwingと同じ値のkotoが反映される。oldSwingで誰かに送金した場合old-chainに対して変更が加えられる。受け取った相手のoldSwingには残高が変更されるが、newSwingの値は変更されない（同じアドレスだが新チェーンを参照しているため）  

> Concrete example  
> When newSwing is started after HF, koto of the same value as oldSwing is reflected. When remitting to someone with oldSwing Changes are made to old-chain. The balance is changed to the oldSwing of the receiving party, but the value of newSwing is not changed (because it refers to the same chain but a new chain)  





