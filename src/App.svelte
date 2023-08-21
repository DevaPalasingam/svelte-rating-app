<script lang="ts">
  import TailwindCss from "./lib/TailwindCSS.svelte";
  import FeedbackList from "./components/FeedbackList.svelte";

  let feedback = [
    {
      id: 1,
      rating: 10,
      text: "Despite the constant negative ipsum covfefe. Sadly, it’s no longer a 10. The best taco bowls are made in Trump Tower Grill.",
    },
    {
      id: 2,
      rating: 3,
      text: "It could be Russia, but it could also be China. It's an art you're basically born with. It's not nice. Lorem Ipsum best not make any more threats to your website. They’re bringing misspellings. We are going to make placeholder text great again. ",
    },
    {
      id: 3,
      rating: 7,
      text: "I think my strongest asset maybe by far is my temperament. That’s what people want, they want placeholder text to be great again.",
    },
  ];
</script>

<TailwindCss />

<main>
  <FeedbackList {feedback} />
</main>
