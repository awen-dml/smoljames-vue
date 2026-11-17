<script setup>

</script>

<template>
  <section id="welcome">
    <div class="beneficts">
      <h2>Complete Your Program <br/>if you want...</h2>
      <div>
        <p>✅ Follow a simple program with proven result.</p>
        <p>✅ Get fit, healthy, and confident.</p>
        <p>✅ Learn more about gym, training and technique.</p>
      </div>
    </div>
    <div>
      <h3>The Training Plan</h3>
      <p>This training plan follows a structure known as the
        <strong>Bro Split</strong>
      </p>
      <h5><i>Push &rarr; Pull &rarr; Legs &rarr; Repeat</i></h5>
    </div>
    <div class="card">
      <h3>🔥 Your Challenge</h3>
      <p>Complete the program and see the results for yourself! <br>Do you accept?</p>
      <button>Begin &rarr;</button>
    </div>
  </section>
</template>

<style scoped>
  #welcome,
  .challenge,
  .beneficts{
    display: flex;
    flex-direction: column;
  }

  #welcome {
    gap: 1.5rem;
  }

  .beneficts {
    gap: 0.5rem;
  }

  .challenge {
    gap: 0.2rem;
  }

  @media (min-width: 640px) {
    #welcome {
      gap: 2rem;
      padding: 1rem 0;
    }
    .beneficts {
      gap: 1rem;
    }
  }
</style>
