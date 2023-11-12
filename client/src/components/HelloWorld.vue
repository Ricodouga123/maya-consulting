<template>
  <v-container>
    <v-row class="text-center">
      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Why TMT?
        </h1>

        <p class="subheading font-weight-regular">

We understand that you have a lot of choices when it comes to IT services, and we appreciate the trust that our clients place in us when they choose our small company for their challenging and complex projects. 

Choosing our service means partnering with a team of professionals with a wealth of experience in the big data industry. Our team members have spent more than 20 years working in the database area, giving them a deep understanding of the intricacies of this field. We are confident in delivering exceptional results that meet your business needs.

Furthermore, we are an agile enterprise that can provide the flexibility and responsiveness that larger companies may not match. As a small company, we can work overtime and on holidays to ensure that your needs are met promptly. We don't have the trappings that can slow down larger organizations, such as multiple departments, that require coordination and sign-off for every decision. This means we can respond quickly to your inquiries, provide fast turnaround times, and give you the personalized attention your business deserves.

We also have extensive experience in software development and large-scale project management, with over 20 years of experience in these fields. Our team of software developers has experience in a wide range of programming languages and frameworks, allowing us to provide custom software solutions that meet the specific needs of your business. 

Whether you need a custom software solution, help with project management, or expert advice on optimizing your data and databases, our team has the knowledge and experience to help you achieve your goals. We understand your business is unique, and we work closely with you to develop solutions that meet your specific needs. With our extensive experience, we can help your business in today's competitive landscape.

        </p>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          What's next?
        </h2>

        <v-row justify="center">
          If you're interested in our services, we would love to hear from you. Please don't hesitate to contact us by email at info@tmt.com. Our team of experts is always ready to answer any questions you may have and provide you with a free consultation to assess your specific needs. We pride ourselves on delivering exceptional customer service and are committed to providing timely and personalized responses to all inquiries. So, whether you're a small business owner or a large corporation, don't hesitate to reach out to us today to see how we can help take your data power to the next level.


Contact Us

Email address: info@tmt.com

        </v-row>
      </v-col>

    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
