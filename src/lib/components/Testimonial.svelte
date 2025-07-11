<script>
  const data = [
    {
      title: "I was only 19...",
      text: "I was only 19 when Phil started making comments about my body. At first, I brushed it off—thinking maybe I was overreacting. But it escalated. He cornered me after hours one day, and I froze. I never reported it. I felt ashamed and afraid of losing my job. But reading other women’s stories helped me realize I wasn’t alone. That was the first step toward healing.",
      name: "Anonymous, California",
    },
    {
      title: "He was a mentor to me...",
      text: "He was someone I looked up to—respected in our field, always surrounded by admiration. When he touched me inappropriately during a business trip, I told myself it must’ve been a misunderstanding. But it wasn’t. I learned later that I wasn’t the only one. Speaking out wasn’t easy, but it was necessary. This movement helped me find my voice.",
      name: "Jasmine, New York",
    },
    {
      title: "It happened in college...",
      text: "I never thought I’d become a ‘statistic.’ But it happened in college. A guy in my program—someone everyone liked—started messaging me constantly, pushing boundaries. One night, he didn’t take no for an answer. I stayed silent for years. I’m still healing. But pages like this remind me I matter. We all do.",
      name: "Tasha, Illinois",
    },
    {
      title: "He said no one would believe me...",
      text: "He said no one would believe me. That’s what they do—use fear to keep us quiet. But today, I speak not just for me, but for every woman who’s been silenced. We believe you. I believe you.",
      name: "Survivor, Texas",
    },
    {
      title: "I found strength through others...",
      text: "After what happened, I blamed myself. I thought maybe I’d led him on somehow. But I know now: It wasn’t my fault. It was his choice. Reading the stories of other survivors gave me courage. If you’re reading this and feeling scared—please know: you are not alone.",
      name: "Melissa, Oregon",
    },
    {
      title: "The power imbalance was real...",
      text: "He was in charge—older, respected, and charming to everyone else. But behind closed doors, he manipulated me and crossed lines I didn’t know how to stop. I thought speaking up would ruin my reputation. Instead, staying silent nearly broke me. I share my story now so others know: you don’t have to carry this alone.",
      name: "Erica, Georgia",
    },
    {
      title: "They brushed it off as 'just flirting'...",
      text: "When I finally told someone, they said he was probably just flirting. But it wasn’t flirting—it was coercion, and it left scars I’m still unpacking. This isn’t about attention or revenge. It’s about truth, accountability, and protecting others. I’m standing in my truth now.",
      name: "Renee, Washington",
    },
    {
      title: "Years later, it still affects me...",
      text: "It happened over a decade ago, but I still think about it all the time. The way he used his position to intimidate and violate me. I buried it for so long. But when I saw other women telling their stories, something inside me unlocked. Sharing mine is painful—but it’s also powerful.",
      name: "Carla, Minnesota",
    },
    {
      title: "He made me doubt my own memory...",
      text: "He was so manipulative, I started doubting my own memory. He’d say things like, ‘You’re imagining it,’ or ‘Don’t be so sensitive.’ It wasn’t until years later, in therapy, that I fully understood what he did. Speaking out now is my way of reclaiming my voice.",
      name: "Natalie, Colorado",
    },
    {
      title: "It started with compliments...",
      text: "At first, it was just compliments. Then it became comments about my clothes, then 'accidental' touches. I kept thinking maybe I was overreacting, until he cornered me in the supply closet. I didn’t report it—he was the boss’s friend. But now, I understand it was never my fault. I'm finally finding peace in speaking out.",
      name: "Lauren, Michigan",
    },
    {
      title: "I was afraid of ruining his career...",
      text: "He was well-liked, charming, and respected. I was afraid that if I said anything, people would think I was trying to ruin his career. But what about mine? What about my safety and sanity? I kept quiet for too long. Sharing my story now is a way to stop protecting people who abuse power.",
      name: "Amira, Florida",
    },
    {
      title: "No one saw what I saw...",
      text: "To everyone else, he was a great guy—helpful, supportive, friendly. But when we were alone, it was a different story. He would say things, touch me in ways that made my skin crawl. When I tried to explain, people didn’t believe me. Now I know that just because others didn’t see it, doesn’t mean it wasn’t real.",
      name: "Sophie, Nevada",
    },
    {
      title: "He used kindness as a cover...",
      text: "He was always so 'nice'—bringing coffee, checking in, acting like a friend. But then came the messages, the pressure, the invasion of my boundaries. I felt gaslighted into thinking I was imagining it. I wasn't. Abusers often hide behind kindness. I’ve learned to trust my instincts again.",
      name: "Dana, Massachusetts",
    },
  ];
</script>

<main>
  <section class="container">
    <div>
      <h2>Your story deserves to be heard.</h2>
      <p>
        Don't allow Phil to silence your suffering; many of his victims have
        already taken the first step and voiced their experiences.
      </p>
      <a href="mailto:">Share your voice</a>
    </div>
    <ul>
      {#each data as { title, text, name }}
        <article class="card">
          <header>
            <h3>{title}</h3>
          </header>
          <p>{text}</p>
          <footer>
            <h2>{name}</h2>
          </footer>
        </article>
      {/each}
    </ul>
  </section>
</main>

<style>
  ul {
    /* padding: 1rem; */
    margin: 2rem 0;
  }
  article {
    border: 1px solid darkgray;
    /* border-radius: 2rem; */
    /* overflow: hidden; */
  }
  h2,
  h3,
  p {
    margin: 0;
  }
</style>
