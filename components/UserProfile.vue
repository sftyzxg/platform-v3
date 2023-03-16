<template>
  <main>
    <div class="h-32 bg-gray-200">This is the banner to be designed</div>
    <div class="h-16 pt-6 pl-4 border-2 border-gray-200">
      <svg
        class="w-6 h-6 float-left mr-2"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
        />
      </svg>
      <div class="font-noto font-bold text-6 leading-6 float-left">
        {{ id }}
      </div>
      <svg
        class="w-6 h-6 float-right mr-4"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        strokeWidth="{1.5}"
        stroke="currentColor"
        className="w-6 h-6"
      >
        <path
          strokeLinecap="round"
          strokeLinejoin="round"
          d="M12 6.75a.75.75 0 110-1.5.75.75 0 010 1.5zM12 12.75a.75.75 0 110-1.5.75.75 0 010 1.5zM12 18.75a.75.75 0 110-1.5.75.75 0 010 1.5z"
        />
      </svg>
      <svg
        class="w-6 h-6 float-right mr-2"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        strokeWidth="{1.5}"
        stroke="currentColor"
        className="w-6 h-6"
      >
        <path
          strokeLinecap="round"
          strokeLinejoin="round"
          d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z"
        />
      </svg>
    </div>
    <div class="h-48 relative">
      <div class="h-32 bg-red-500"></div>
      <img
        class="
          absolute
          float-left
          left-1/2
          top-9
          h-36
          w-36
          rounded-full
          transform
          -translate-x-1/2
          border-4 border-white
        "
        src="https://firebasestorage.googleapis.com/v0/b/wedance-4abe3.appspot.com/o/media%2FtvR012ArEpQhCJdPHh6G7sLuqoO2%2F85cc5d77-6212-4707-85e0-24bdf72b1c7c?alt=media&token=2872dc07-fa22-46b7-8f0e-41c935fc6345"
      />
    </div>
    <div class="h-28 pt-2 pd-2 g-4 border-b-2 border-gray-200">
      <div
        class="
          text-3xl
          font-bold
          tracking-tight
          font-noto
          text-center
          drop-shadow-lg
        "
      >
        {{ name }}
      </div>
      <div class="font-noto text-center pt-2">
        {{ title }}
      </div>
      <div class="font-noto text-center text-gray-500">
        {{ views }} views • {{ subscribers }} subscribers
      </div>
    </div>
    <div class="h-24 pt-2 g-4">
      <div>
        <div class="h-8 w-1/3 inline-block">
          <div
            class="
              relative
              left-1/2
              h-8
              w-8
              rounded-full
              bg-white
              transform
              -translate-x-1/2
              border-b-2 border-gray-200
            "
          >
            <svg
              class="
                relative
                left-1/2
                top-1/2
                w-6
                h-6
                transform
                -translate-x-1/2 -translate-y-1/2
              "
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              className="w-6 h-6"
            >
              <path
                d="M1.5 8.67v8.58a3 3 0 003 3h15a3 3 0 003-3V8.67l-8.928 5.493a3 3 0 01-3.144 0L1.5 8.67z"
              />
              <path
                d="M22.5 6.908V6.75a3 3 0 00-3-3h-15a3 3 0 00-3 3v.158l9.714 5.978a1.5 1.5 0 001.572 0L22.5 6.908z"
              />
            </svg>
          </div>
        </div>
        <div class="h-8 w-1/3 inline-block">
          <div
            class="
              relative
              left-1/2
              h-8
              w-8
              rounded-full
              bg-white
              transform
              -translate-x-1/2
              border-b-2 border-gray-200
            "
          >
            <svg
              class="
                relative
                left-1/2
                top-1/2
                w-6
                h-6
                transform
                -translate-x-1/2 -translate-y-1/2
              "
              width="24px"
              height="24px"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              xml:space="preserve"
              xmlns:serif="http://www.serif.com/"
              style="
                fill-rule: evenodd;
                clip-rule: evenodd;
                stroke-linejoin: round;
                stroke-miterlimit: 1.41421;
              "
            >
              <path
                id="telegram-4"
                d="M12,0c-6.626,0 -12,5.372 -12,12c0,6.627 5.374,12 12,12c6.627,0 12,-5.373 12,-12c0,-6.628 -5.373,-12 -12,-12Zm3.224,17.871c0.188,0.133 0.43,0.166 0.646,0.085c0.215,-0.082 0.374,-0.267 0.422,-0.491c0.507,-2.382 1.737,-8.412 2.198,-10.578c0.035,-0.164 -0.023,-0.334 -0.151,-0.443c-0.129,-0.109 -0.307,-0.14 -0.465,-0.082c-2.446,0.906 -9.979,3.732 -13.058,4.871c-0.195,0.073 -0.322,0.26 -0.316,0.467c0.007,0.206 0.146,0.385 0.346,0.445c1.381,0.413 3.193,0.988 3.193,0.988c0,0 0.847,2.558 1.288,3.858c0.056,0.164 0.184,0.292 0.352,0.336c0.169,0.044 0.348,-0.002 0.474,-0.121c0.709,-0.669 1.805,-1.704 1.805,-1.704c0,0 2.084,1.527 3.266,2.369Zm-6.423,-5.062l0.98,3.231l0.218,-2.046c0,0 3.783,-3.413 5.941,-5.358c0.063,-0.057 0.071,-0.153 0.019,-0.22c-0.052,-0.067 -0.148,-0.083 -0.219,-0.037c-2.5,1.596 -6.939,4.43 -6.939,4.43Z"
              />
            </svg>
          </div>
        </div>
        <div class="h-8 w-1/3 inline-block">
          <div
            class="
              relative
              left-1/2
              h-8
              w-8
              rounded-full
              bg-white
              transform
              -translate-x-1/2
              border-b-2 border-gray-200
            "
          >
            <svg
              class="
                relative
                left-1/2
                top-1/2
                w-6
                h-6
                transform
                -translate-x-1/2 -translate-y-1/2
              "
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
            >
              <path
                d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm3 8h-1.35c-.538 0-.65.221-.65.778v1.222h2l-.209 2h-1.791v7h-3v-7h-2v-2h2v-2.308c0-1.769.931-2.692 3.029-2.692h1.971v3z"
              />
            </svg>
          </div>
        </div>
      </div>
      <div>
        <div class="h-8 w-1/3 inline-block">
          <div
            class="
              relative
              left-1/2
              h-8
              w-8
              rounded-full
              bg-white
              transform
              -translate-x-1/2
              border-b-2 border-gray-200
            "
          >
            <svg
              class="
                relative
                left-1/2
                top-1/2
                w-6
                h-6
                transform
                -translate-x-1/2 -translate-y-1/2
              "
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
            >
              <path
                d="M14.829 6.302c-.738-.034-.96-.04-2.829-.04s-2.09.007-2.828.04c-1.899.087-2.783.986-2.87 2.87-.033.738-.041.959-.041 2.828s.008 2.09.041 2.829c.087 1.879.967 2.783 2.87 2.87.737.033.959.041 2.828.041 1.87 0 2.091-.007 2.829-.041 1.899-.086 2.782-.988 2.87-2.87.033-.738.04-.96.04-2.829s-.007-2.09-.04-2.828c-.088-1.883-.973-2.783-2.87-2.87zm-2.829 9.293c-1.985 0-3.595-1.609-3.595-3.595 0-1.985 1.61-3.594 3.595-3.594s3.595 1.609 3.595 3.594c0 1.985-1.61 3.595-3.595 3.595zm3.737-6.491c-.464 0-.84-.376-.84-.84 0-.464.376-.84.84-.84.464 0 .84.376.84.84 0 .463-.376.84-.84.84zm-1.404 2.896c0 1.289-1.045 2.333-2.333 2.333s-2.333-1.044-2.333-2.333c0-1.289 1.045-2.333 2.333-2.333s2.333 1.044 2.333 2.333zm-2.333-12c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm6.958 14.886c-.115 2.545-1.532 3.955-4.071 4.072-.747.034-.986.042-2.887.042s-2.139-.008-2.886-.042c-2.544-.117-3.955-1.529-4.072-4.072-.034-.746-.042-.985-.042-2.886 0-1.901.008-2.139.042-2.886.117-2.544 1.529-3.955 4.072-4.071.747-.035.985-.043 2.886-.043s2.14.008 2.887.043c2.545.117 3.957 1.532 4.071 4.071.034.747.042.985.042 2.886 0 1.901-.008 2.14-.042 2.886z"
              />
            </svg>
          </div>
        </div>
        <div class="h-8 w-1/3 inline-block">
          <div
            class="
              relative
              left-1/2
              h-8
              w-8
              rounded-full
              bg-white
              transform
              -translate-x-1/2
              border-b-2 border-gray-200
            "
          >
            <svg
              class="
                relative
                left-1/2
                top-1/2
                w-6
                h-6
                transform
                -translate-x-1/2 -translate-y-1/2
              "
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
            >
              <path
                d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm6.066 9.645c.183 4.04-2.83 8.544-8.164 8.544-1.622 0-3.131-.476-4.402-1.291 1.524.18 3.045-.244 4.252-1.189-1.256-.023-2.317-.854-2.684-1.995.451.086.895.061 1.298-.049-1.381-.278-2.335-1.522-2.304-2.853.388.215.83.344 1.301.359-1.279-.855-1.641-2.544-.889-3.835 1.416 1.738 3.533 2.881 5.92 3.001-.419-1.796.944-3.527 2.799-3.527.825 0 1.572.349 2.096.907.654-.128 1.27-.368 1.824-.697-.215.671-.67 1.233-1.263 1.589.581-.07 1.135-.224 1.649-.453-.384.578-.87 1.084-1.433 1.489z"
              />
            </svg>
          </div>
        </div>
        <div class="h-8 w-1/3 inline-block">
          <div
            class="
              relative
              left-1/2
              h-8
              w-8
              rounded-full
              bg-white
              transform
              -translate-x-1/2
              border-b-2 border-gray-200
            "
          >
            <svg
              class="
                relative
                left-1/2
                top-1/2
                w-6
                h-6
                transform
                -translate-x-1/2 -translate-y-1/2
              "
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              version="1.1"
              width="256"
              height="256"
              viewBox="0 0 256 256"
              xml:space="preserve"
            >
              <defs></defs>
              <g
                style="
                  stroke: none;
                  stroke-width: 0;
                  stroke-dasharray: none;
                  stroke-linecap: butt;
                  stroke-linejoin: miter;
                  stroke-miterlimit: 10;
                  fill: none;
                  fill-rule: nonzero;
                  opacity: 1;
                "
                transform="translate(1.4065934065934016 1.4065934065934016) scale(2.81 2.81)"
              >
                <path
                  d="M 45 0 C 20.147 0 0 20.147 0 45 c 0 24.853 20.147 45 45 45 s 45 -20.147 45 -45 C 90 20.147 69.853 0 45 0 z M 72.039 33.277 v 6.758 c -3.187 0.001 -6.283 -0.623 -9.203 -1.855 c -1.878 -0.793 -3.627 -1.814 -5.227 -3.048 l 0.048 20.801 c -0.02 4.684 -1.873 9.085 -5.227 12.4 c -2.73 2.698 -6.188 4.414 -9.937 4.97 c -0.881 0.13 -1.777 0.197 -2.684 0.197 c -4.013 0 -7.823 -1.3 -10.939 -3.698 c -0.586 -0.452 -1.147 -0.941 -1.681 -1.468 c -3.635 -3.593 -5.509 -8.462 -5.194 -13.584 c 0.241 -3.899 1.802 -7.618 4.404 -10.532 c 3.443 -3.857 8.26 -5.998 13.41 -5.998 c 0.906 0 1.803 0.068 2.684 0.198 v 2.499 v 6.951 c -0.835 -0.275 -1.727 -0.427 -2.656 -0.427 c -4.705 0 -8.512 3.839 -8.442 8.548 c 0.045 3.013 1.69 5.646 4.118 7.098 c 1.141 0.682 2.453 1.105 3.853 1.182 c 1.097 0.06 2.151 -0.093 3.126 -0.415 c 3.362 -1.111 5.787 -4.268 5.787 -7.992 l 0.011 -13.93 V 16.5 h 9.307 c 0.009 0.922 0.103 1.822 0.276 2.694 c 0.702 3.529 2.692 6.591 5.46 8.678 c 2.414 1.821 5.42 2.9 8.678 2.9 c 0.002 0 0.029 0 0.027 -0.002 V 33.277 z"
                  style="
                    stroke: none;
                    stroke-width: 1;
                    stroke-dasharray: none;
                    stroke-linecap: butt;
                    stroke-linejoin: miter;
                    stroke-miterlimit: 10;
                    fill: rgb(0, 0, 0);
                    fill-rule: nonzero;
                    opacity: 1;
                  "
                  transform=" matrix(1 0 0 1 0 0) "
                  stroke-linecap="round"
                />
              </g>
            </svg>
          </div>
        </div>
      </div>
      <div class="h-16 p-2 g-2">
        <button
          v-if="!subscribed"
          class="w-full bg-black text-white py-2 px-4 rounded-full"
          @click="subscribe"
        >
          Subscribe
        </button>
        <button
          v-else
          class="
            w-full
            bg-white
            text-black
            py-2
            px-4
            rounded-full
            border-2 border-gray-200
          "
          @click="subscribe"
        >
          Subscribed
        </button>
      </div>
      <div class="h-16 p-2">
        <div class="h-10 w-1/5 inline-block">
          <button
            v-if="currentwindow == 'About'"
            class="h-10 w-full bg-black text-white rounded-full"
          >
            About
          </button>
          <button
            v-else
            class="
              w-full
              h-10
              bg-white
              text-black
              rounded-full
              border-2 border-gray-200
            "
            @click="switchwindow('About')"
          >
            About
          </button>
        </div>
        <div class="h-10 w-1/5 inline-block">
          <button
            v-if="currentwindow == 'Feed'"
            class="h-10 w-full bg-black text-white rounded-full"
          >
            Feed
          </button>
          <button
            v-else
            class="
              h-10
              w-full
              bg-white
              text-black
              rounded-full
              border-2 border-gray-200
            "
            @click="switchwindow('Feed')"
          >
            Feed
          </button>
        </div>
        <div class="h-10 w-3/5 inline-block">
          <button
            v-if="currentwindow == 'Events'"
            class="h-10 w-full bg-black text-white rounded-full"
          >
            Upcoming Events
          </button>
          <button
            v-else
            class="
              h-10
              w-full
              bg-white
              text-black
              rounded-full
              border-2 border-gray-200
            "
            @click="switchwindow('Events')"
          >
            Upcoming Events
          </button>
        </div>
      </div>
      <div v-if="currentwindow == 'About'" class="p-4 h-56">{{ about }}</div>
      <div v-if="currentwindow == 'Feed'" class="p-4 h-56">{{ feed }}</div>
      <div v-if="currentwindow == 'Events'" class="p-4 h-56">{{ event }}</div>
    </div>
  </main>
</template>

<script>
export default {
  data() {
    return {
      subscribed: false,
      currentwindow: 'About',
      subscribers: 13,
      views: 348,
    }
  },
  props: {
    name: {
      type: String,
      default: 'Alex Razbakov',
    },
    id: {
      type: String,
      default: 'alexrazbakov',
    },
    title: {
      type: String,
      default: 'Founder of WeDance',
    },
    about: {
      type: String,
      default:
        'Founder of WeDance. Salsa Cubana Instructor. Looking for dancer partner to practice.Salsa Cubana Instructor @MontunoClub. Salsa, Bachata, Kizomba Dancer. IT Consultant. Software Developer.I also love to dance Urban Kiz and Bachata Dominicana. Looking for partner to practice online lessons with @albertovaldes.I love to culture travel and dance helps me to connect even better with locals, it’s just like a universal language to communicate anywhere.',
    },
    feed: {
      type: String,
      default: 'Feed',
    },
    events: {
      type: String,
      default: 'Events',
    },
  },
  methods: {
    subscribe() {
      this.subscribed = !this.subscribed
      if (this.subscribed) {
        this.subscribers = this.subscribers + 1
      } else {
        this.subscribers = this.subscribers - 1
      }
    },
    switchwindow(window) {
      this.currentwindow = window
    },
  },
}
</script>

<style></style>
