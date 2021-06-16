<template>
  <div class="banner-area">
    <h2>microgreens or super food of the future?</h2>
  </div>
  <div class="content-area">
    <div class="wrapper">
      <h2>the answer:</h2>
      <p>
        Microgreens are not only a superfood but they are also the key to a more
        sustainable future. Microgreens are young vegetables that are harvested
        before they can grow full size. The reason this is important is because
        when the greens are young and small they are more nutrient dense. This
        means you can consume way less than you would a normal sized veggie and
        still get the same if not more nutrition from the microgreens. There's
        current
        <a
          href="https://www.sciencedirect.com/science/article/abs/pii/S0889157514001513"
          >research</a
        >
        suggesting microgreens can have up to nine times higher nutrient levels
        than mature greens. This tiny but powerful green is they key to our
        future.
      </p>
      <p>
        As the world's population grows, farmers continually have to meet more
        and more demand every year. This not only places a growing burden on
        farmers but it also leaves us wondering if eventually we'll run out of
        supply to meet the demand. A solution to this is "vertical farming" or,
        more precisely, microgreens. Microgreens are a solution because of many
        different factors with its grow time being a huge part. Since the greens
        are harvested young, it takes a lot less time waiting for them to grow.
        Also due to their size and how they're grown it makes them an amazing
        crop for vertical farming. Take a look at this awesome farm and you'll
        see what I mean.
      </p>
      <img
        class="vfarm1"
        src="https://weburbanist.com/wp-content/uploads/2016/05/vertical-farming.jpg"
        alt="Picture of Vertical Farm"
      />
      <h3>Health Benefits</h3>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.vfarm1 {
  width: 900px;
  height: 600px;
}

body {
  text-align: center;
  margin: 0 auto;
}

.wrapper {
  width: 75%;
  margin-right: auto;
  margin-left: auto;
}
/* talk to christian about width */
.banner-area {
  width: 100%;
  height: 350px;
  position: fixed;
  top: 100px;
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("https://vertical-farming.net/wp-content/uploads/2018/05/vertical-770x400.jpeg");
  background-size: cover;
  background-position: center center;
}

.banner-area h2 {
  padding-top: 4%;
  font-size: 70px;
  font-family: Arial, Helvetica, sans-serif;
  text-transform: uppercase;
  color: rgb(224, 224, 224);
}

.content-area {
  width: 100%;
  position: relative;
  top: 450px;
  background: whitesmoke;

  height: 1500px;
}

.content-area h2 {
  font-family: poppins;
  letter-spacing: 3px;
  padding-top: 30px;
  font-size: 30px;
  margin: 0;
  text-transform: uppercase;
}
.content-area p {
  padding: 2% 0px;
  font-family: poppins;
  line-height: 30px;
  font-size: 18px;
}
</style>
