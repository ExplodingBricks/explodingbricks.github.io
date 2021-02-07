<template>
  <main class="container mx-auto px-4 mt-28 md:mt-20 h-screen">
    <h1
      class="text-4xl mb-6 tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl"
    >
      About
    </h1>

    <div class="prose">
      <h1 id="exploding-bricks">Exploding Bricks</h1>
      <p>
        Exploding Bricks is a small FLL Robotics team.
      </p>
      <h2 id="our-stats">Our stats</h2>
      <table>
        <thead>
          <tr>
            <th>Year</th>
            <th>Language</th>
            <th>Robots</th>
            <th>Members</th>
            <th>Score</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>2020</td>
            <td>Python</td>
            <td>
              <img
                class="emoji"
                title=":smile:"
                alt=":smile:"
                src="https://github.githubassets.com/images/icons/emoji/unicode/1f604.png"
                height="20"
                width="20"
              />
            </td>
            <td>5</td>
            <td>
              <img
                class="emoji"
                title=":man_shrugging:"
                alt=":man_shrugging:"
                src="https://github.githubassets.com/images/icons/emoji/unicode/1f937-2642.png"
                height="20"
                width="20"
              />
            </td>
          </tr>
          <tr>
            <td>2019</td>
            <td>EV3-G</td>
            <td>
              <img
                class="emoji"
                title=":smile:"
                alt=":smile:"
                src="https://github.githubassets.com/images/icons/emoji/unicode/1f604.png"
                height="20"
                width="20"
              />
            </td>
            <td>6</td>
            <td>#</td>
          </tr>
        </tbody>
      </table>
      <p>
        This year, we decided to use MicroPython because we felt that EV3-G was
        old, and slow. We looked into EV3 Classroom, but we also felt that it
        didn’t have the same level of features. We tested out Micropython paired
        with EV3-DEV, and loved it.
      </p>
      <p>
        Another innovation this year was using Studio 2.0. This is a software that lets us digitally store, and create instructions of our robots and attachments. This has been really helpful this year as it lets us build exact copies of our robots, and share them among the team.
      </p>
    </div>
  </main>
</template>
<script>
export default {
  head() {
    return {
      title: `About - Exploding Bricks`
    };
  }
};
</script>
