<template>
  <section>
    <img class="about-group-banner" src="https://owddm.github.io/public/images/discord/event-photos/1089404389707481099/1089404385362186250/P1004543@l.webp" alt="" />
    <div class="about-content">
      <h1 class="about-title">Osaka/Kyoto Web Designers and Developers Meetup</h1>
      <div class="about-description-container">
        <div>
          <p>
            Wow!
            This 👆 is a mouthful!
            We chose this name long ago to make the group easy to find.
            We have gotten to like it, but it is a tad long!
            For short, we go by “OWDDM” - for those able to pronounce it.
          </p>
          <p>
            The "O" stands for <em>Osaka</em>, the vibrant, second-largest metropolis in Japan.
            This is where the meetup group started and where we still do most of our events.
            Recently, we have also been in <em>Kyoto</em> quite a bit.
            For that reason, we opened the "KWDDM".
            For brevity, we tend to call the group <em>OWDDM</em> and use "O" for “owesome”. 😛
          </p>
          <p>
            <em>Alright,</em> the OWDDM is a volunteer, non-profit group that organizes meetups in Kansai.
            We usually have one meetup per month and region.
            Usually, during the meetups, one or two community members present about a topic of their choosing.
            Occasionally, we hold other events such as Hanami’s, hikes, and other get-togethers.
          </p>
          <p>
            Our events are in English and about a broad range of topics.
            We want to <em>invite people from all walks of web-life</em> and ask them to present things they enjoy.
            Frontend, Backend, Design, SEO, Cloud management, Games... many topics got a bit of time in the past.
            While its not part of the main events, often the members go out for dinner after the meetup.
          </p>
        </div>
        <div>
          <p>
            わぁーい！<!--
            -->この👆は口癖です！<!--
            -->私たちは、グループを見つけやすくするために、ずっと前にこの名前を選びました。<!--
            -->この名前を気に入っていますが、ちょっと長いです！<!--
            -->略して、私たちは「OWDDM」で通っています… 発音できる人たちのために「オー・ダブルユー・ディ・ディ・エム」。
          </p>
          <p>
            「O」は大阪を意味します。<!--
            -->ミートアップグループが始まった場所であり、今でもほとんどのイベントをここで行っています。<!--
            -->最近は、京都にもよく行くようになりました。<!--
            -->そのため、「KWDDM」をオープンしました。<!--
            -->簡潔にするために、私たちはこのグループを OWDDM と呼び、「O」の意味を「オーサム」と傾向があります。<!--
            -->😛
          </p>
          <p>
            さて、OWDDM は関西でミートアップを開催するボランティアで非営利のグループです。<!--
            -->私たちは通常、月と地域に1回のミートアップを開催しています。<!--
            -->通常、ミートアップでは、1人または2人のコミュニティメンバーが、自分の選んだトピックについて発表します。<!--
            -->時には、花見、ハイキング、その他の集まりなどのイベントも開催しています。
          </p>
          <p>
            イベントは、英語で、幅広いトピックについて行われます。<!--
            -->私たちは、ウェブライフのあらゆる分野から人々を招き、彼らが楽しんでいることを発表してもらいたいと考えています。<!--
            -->フロントエンド、バックエンド、デザイン、SEO、クラウド管理、ゲーム…様々なトピックが過去に少し時間を割いたことがあります。<!--
            -->イベントの内容ではないですが、ミートアップ後に参加者は居酒屋に行くこともよくあります。
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
section {
  margin-top: 0;
}
.about-group-banner {
  clip-path: inset(180px 0px 180px 0px);
  margin-top: -180px;
  margin-bottom: -180px;
  width: 100%;
}
.about-content {
  padding: 0 env(safe-area-inset-right) 0 env(safe-area-inset-left);
}

.about-title {
  margin: 2rem;
  line-height: normal;
}

.about-description-container {
  display: flex;
  margin-bottom: 2rem;
  padding: 0 2rem;
  gap: 2rem;
}
.about-description-container p {
  margin-bottom: 0.8em;
  text-indent: 0.5em;
}

@media only screen and (max-width: 768px) {
  .about-group-banner {
    clip-path: inset(50px 0px 20px 0px);
    margin-top: -50px;
    margin-bottom: -20px;
  }
  .about-description-container {
    flex-direction: column;
    gap: 2rem;
  }
}


</style>
