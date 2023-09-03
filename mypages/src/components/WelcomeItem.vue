<template>
  <div class="item">
    <i>
      <slot name="icon"></slot>
    </i>
    <div class="details">
      <h3>
        <slot name="heading"></slot>
      </h3>
      <div class="relative">
        <div class="prostokat bg-slate-400 w-full h-96 z-1">
          <button @click.native="showTrojkat()">klik.native</button>
        </div>
        {{ trojkatDisplayBlock }}
        <div v-if="trojkatDisplayBlock" class="figury flex w-full">
          <button @click.native="showTrojkat()">klik.native</button>

          <div class="columns-2 riotbar-application-switcher-content-wrapper">
            <div
              class="columns-3 _15z73Qt6c5oxP96IpesoyN riotbar-application-switcher-links-wrapper"
            >
              <div class="1">
                <div
                  id="riotbar-application-switcher-menu-product-section"
                  class="CrMKKq3PzC5SoglzTS--J"
                >
                  <div
                    id="riotbar-application-switcher-menu-link-title"
                    class="Gi1SpBPREWiusMm1r-LhV riotbar-application-switcher-menu-link-title"
                  >
                    GAMES
                  </div>
                  <div
                    id="riotbar-application-switcher-menu-link-wrapper"
                    class="_3op4vibCiPw1kAujQCjpup riotbar-application-switcher-menu-link-wrapper"
                  >
                    <!-- _________________________________ -->
                    <div v-for="item in section1A" :key="item">
                      <a :href="item.href" target="_blank">
                        <div class="">
                          <div
                            class="riotbar-application-switcher-menu-product-card-wrapper visible"
                          >
                            <div class=""></div>
                            <!-- <img
                              class="_2vBqj2b0PZ3_l_JDGbzr0O"
                              src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt69961ce901c892c5/63ead58ad6b15b22437be7e1/LOL_KA23_Product-Card_RBAR_1280x720_FINAL.jpg??&amp;format=pjpg&amp;quality=85"
                              alt="LEAGUE OF LEGENDS"
                              title="LEAGUE OF LEGENDS"
                            /> -->
                            <div
                              class=""
                              style="
                                background-image: radial-gradient(
                                  160.43% 179.54% at 100.43% 100%,
                                  rgb(9, 20, 40) 0%,
                                  rgb(10, 10, 10) 70%
                                );
                              "
                            >
                              <div class="">
                                <div
                                  class="riotbar-application-switcher-menu-product-card-frame-title"
                                >
                                  <!-- <img
                                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt17d9df62ff2abfdb/615a85178f1f7b55821485e4/LOL.svg?"
                                    alt="LEAGUE OF LEGENDS"
                                    title="LEAGUE OF LEGENDS"
                                  /> -->
                                </div>
                                <div
                                  id="riotbar-application-switcher-menu-product-card-frame-description"
                                  class=""
                                >
                                  <span>{{ item.content }}</span>
                                </div>
                                <div class="_2pcY7uH3fjuYGCFH3bbupt">
                                  <div class="">
                                    <div class="">
                                      <svg width="8" height="8" class="" viewBox="0 0 10 10">
                                        <title>platform_windows_transp</title>
                                        <path
                                          d="M0 1.416L4.087.86l.002 3.929-4.084.023L0 1.416zm4.085 3.827l.003 3.933-4.085-.56V5.218l4.082.026zM4.58.79L9.998 0v4.741l-5.418.042V.79zM10 5.279L9.998 10 4.58 9.238l-.008-3.966L10 5.28z"
                                        ></path>
                                      </svg>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                        <span>{{ item.title }}</span>
                      </a>
                    </div>
                  </div>
                </div>
              </div>

              <div class="2">
                <div
                  id="riotbar-application-switcher-menu-product-section"
                  class="CrMKKq3PzC5SoglzTS--J"
                >
                  <div
                    id="riotbar-application-switcher-menu-link-title"
                    class="Gi1SpBPREWiusMm1r-LhV riotbar-application-switcher-menu-link-title"
                  >
                    FORGE<svg class=" " viewBox="0 0 8 5">
                      <title>mainNavArrowDown</title>
                      <path
                        d="M.707 1.707l2.586 2.586a1 1 0 001.414 0l2.586-2.586C7.923 1.077 7.477 0 6.586 0H1.414C.524 0 .077 1.077.707 1.707z"
                        fill="#7E7E7E"
                      ></path>
                    </svg>
                  </div>
                  <div
                    id="riotbar-application-switcher-menu-link-wrapper"
                    class="_3op4vibCiPw1kAujQCjpup riotbar-application-switcher-menu-link-wrapper"
                  >
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://convrgencegame.com/en-us/?utm_medium=card1%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card1"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">CONV/RGENCE</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://hextechmayhem.com/en-us/?utm_medium=card2%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card2"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">HEXTECH MAYHEM</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://www.themageseeker.com/en-us/?utm_medium=card3%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card3"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">THE MAGESEEKER</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://ruinedking.com/en-us/?utm_medium=card4%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card4"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">RUINED KING</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://songofnunu.com/en-us/?utm_medium=card5%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card5"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">SONG OF NUNU</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://riotforgegames.com/en-us/?utm_medium=card6%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card6"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">RIOT FORGE GAMES</span></a
                      >
                    </div>
                  </div>
                </div>
                <div
                  id="riotbar-application-switcher-menu-product-section"
                  class="CrMKKq3PzC5SoglzTS--J"
                >
                  <div
                    id="riotbar-application-switcher-menu-link-title"
                    class="Gi1SpBPREWiusMm1r-LhV riotbar-application-switcher-menu-link-title"
                  >
                    ESPORTS<svg class=" " viewBox="0 0 8 5">
                      <title>mainNavArrowDown</title>
                      <path
                        d="M.707 1.707l2.586 2.586a1 1 0 001.414 0l2.586-2.586C7.923 1.077 7.477 0 6.586 0H1.414C.524 0 .077 1.077.707 1.707z"
                        fill="#7E7E7E"
                      ></path>
                    </svg>
                  </div>
                  <div
                    id="riotbar-application-switcher-menu-link-wrapper"
                    class="_3op4vibCiPw1kAujQCjpup riotbar-application-switcher-menu-link-wrapper"
                  >
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://lolesports.com/?utm_medium=card1%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card1"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">LOL ESPORTS</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://valorantesports.com/?utm_medium=card2%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card2"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">VALORANT ESPORTS</span></a
                      >
                    </div>
                  </div>
                </div>
              </div>
              <div class="3">
                <div
                  id="riotbar-application-switcher-menu-product-section"
                  class="CrMKKq3PzC5SoglzTS--J"
                >
                  <div
                    id="riotbar-application-switcher-menu-link-title"
                    class="Gi1SpBPREWiusMm1r-LhV riotbar-application-switcher-menu-link-title"
                  >
                    ENTERTAINMENT<svg class=" " viewBox="0 0 8 5">
                      <title>mainNavArrowDown</title>
                      <path
                        d="M.707 1.707l2.586 2.586a1 1 0 001.414 0l2.586-2.586C7.923 1.077 7.477 0 6.586 0H1.414C.524 0 .077 1.077.707 1.707z"
                        fill="#7E7E7E"
                      ></path>
                    </svg>
                  </div>
                  <div
                    id="riotbar-application-switcher-menu-link-wrapper"
                    class="_3op4vibCiPw1kAujQCjpup riotbar-application-switcher-menu-link-wrapper"
                  >
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://arcane.com/en-us/?utm_medium=card1%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card1"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">ARCANE</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://universe.leagueoflegends.com/en_US/?utm_medium=card2%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card2"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">UNIVERSE</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://linktr.ee/riotgamesmusic?utm_medium=card3%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card3"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">RIOT GAMES MUSIC</span></a
                      >
                    </div>
                  </div>
                </div>
                <div
                  id="riotbar-application-switcher-menu-product-section"
                  class="CrMKKq3PzC5SoglzTS--J"
                >
                  <div
                    id="riotbar-application-switcher-menu-link-title"
                    class="Gi1SpBPREWiusMm1r-LhV riotbar-application-switcher-menu-link-title"
                  >
                    BUSINESS<svg class=" " viewBox="0 0 8 5">
                      <title>mainNavArrowDown</title>
                      <path
                        d="M.707 1.707l2.586 2.586a1 1 0 001.414 0l2.586-2.586C7.923 1.077 7.477 0 6.586 0H1.414C.524 0 .077 1.077.707 1.707z"
                        fill="#7E7E7E"
                      ></path>
                    </svg>
                  </div>
                  <div
                    id="riotbar-application-switcher-menu-link-wrapper"
                    class="_3op4vibCiPw1kAujQCjpup riotbar-application-switcher-menu-link-wrapper"
                  >
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://www.riotgames.com/en/?utm_medium=card1%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card1"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">RIOT GAMES</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://merch.riotgames.com/en-us/?utm_medium=card2%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card2"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">RIOT MERCH</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://www.leagueoflegends.com/en-us/news/riot-games/hello-riot-mobile-farewell-league/?utm_medium=card3%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card3"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">RIOT MOBILE</span></a
                      >
                    </div>
                    <div class="_3gDCN_2kxChV6TAYM0NU0T">
                      <a
                        href="https://support.riotgames.com/hc/en-us/?utm_medium=card4%2Bwww.riotgames.com&amp;utm_source=riotbar"
                        target="_blank"
                        data-interaction-id="riotbar_app-switcher-card_card4"
                        ><span class="MJOJbeA7pq31QsPgJgGeM">RIOT SUPPORT</span></a
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="Bl2h8pEdr-8QVPq-PNjc6 riotbar-application-switcher-cards-wrapper">
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt69961ce901c892c5/63ead58ad6b15b22437be7e1/LOL_KA23_Product-Card_RBAR_1280x720_FINAL.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="LEAGUE OF LEGENDS"
                    title="LEAGUE OF LEGENDS"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(9, 20, 40) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt17d9df62ff2abfdb/615a85178f1f7b55821485e4/LOL.svg?"
                          alt="LEAGUE OF LEGENDS"
                          title="LEAGUE OF LEGENDS"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>Face off in the ultimate 5v5 battle arena</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt">
                      <div class="GHMgBnj6lwMEIU-yFlqCs">
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 10 10">
                            <title>platform_windows_transp</title>
                            <path
                              d="M0 1.416L4.087.86l.002 3.929-4.084.023L0 1.416zm4.085 3.827l.003 3.933-4.085-.56V5.218l4.082.026zM4.58.79L9.998 0v4.741l-5.418.042V.79zM10 5.279L9.998 10 4.58 9.238l-.008-3.966L10 5.28z"
                            ></path>
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt5db9aeb297bda157/6496633fe9365acb3dc34d39/062723_Ep7_Product_Card_1920x1080.png??&amp;format=pjpg&amp;quality=85"
                    alt="VALORANT"
                    title="VALORANT"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(254, 129, 85) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt7dde242cdb9e437a/61af0ed4d715b5102311d2ee/Valorant.svg?"
                          alt="VALORANT"
                          title="VALORANT"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>Style on your enemies in this 5v5 tactical shooter</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt">
                      <div class="GHMgBnj6lwMEIU-yFlqCs">
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 10 10">
                            <title>platform_windows_transp</title>
                            <path
                              d="M0 1.416L4.087.86l.002 3.929-4.084.023L0 1.416zm4.085 3.827l.003 3.933-4.085-.56V5.218l4.082.026zM4.58.79L9.998 0v4.741l-5.418.042V.79zM10 5.279L9.998 10 4.58 9.238l-.008-3.966L10 5.28z"
                            ></path>
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltfe729ffe29021170/64813b50cc30bbb04ab0456e/TFT_SET923_Riotbar_1920x1080_v004_ASteme.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="TEAMFIGHT TACTICS"
                    title="TEAMFIGHT TACTICS"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(139, 121, 229) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt73ba063c224de13c/620719f19c50e50a64ea776b/TFT_Evergreen_Logo_Bug-Wordmark-Stacked_Final.svg?"
                          alt="TEAMFIGHT TACTICS"
                          title="TEAMFIGHT TACTICS"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>A TEAM-BUILDING BATTLE OF WITS</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt">
                      <div class="GHMgBnj6lwMEIU-yFlqCs">
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 10 10">
                            <title>platform_windows_transp</title>
                            <path
                              d="M0 1.416L4.087.86l.002 3.929-4.084.023L0 1.416zm4.085 3.827l.003 3.933-4.085-.56V5.218l4.082.026zM4.58.79L9.998 0v4.741l-5.418.042V.79zM10 5.279L9.998 10 4.58 9.238l-.008-3.966L10 5.28z"
                            ></path>
                          </svg>
                        </div>
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 7 10">
                            <title>platform_phone_transp</title>
                            <path
                              d="M2.5 8.125a.624.624 0 101.249.001.624.624 0 00-1.249 0zM0 .938v8.125C0 9.58.42 10 .938 10h4.375c.517 0 .937-.42.937-.937V.938A.938.938 0 005.312 0H.938A.938.938 0 000 .938zm.938 8.007v-7.89c0-.065.052-.117.117-.117h4.14c.065 0 .117.052.117.117v7.89a.118.118 0 01-.117.118h-4.14a.118.118 0 01-.117-.118z"
                            ></path>
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt026d2bccb899c112/649b467a66ab62671ffc77f1/LoR_7B2023_HotH_RiotBarApplicationSwitcher_1920x1080_opt.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="LEGENDS OF RUNETERRA"
                    title="LEGENDS OF RUNETERRA"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(208, 130, 62) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt1967c1b8539fb74a/615a85219c76234dd174c18d/Runeterra.svg?"
                          alt="LEGENDS OF RUNETERRA"
                          title="LEGENDS OF RUNETERRA"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>Master every moment in this strategy card game</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt">
                      <div class="GHMgBnj6lwMEIU-yFlqCs">
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 10 10">
                            <title>platform_windows_transp</title>
                            <path
                              d="M0 1.416L4.087.86l.002 3.929-4.084.023L0 1.416zm4.085 3.827l.003 3.933-4.085-.56V5.218l4.082.026zM4.58.79L9.998 0v4.741l-5.418.042V.79zM10 5.279L9.998 10 4.58 9.238l-.008-3.966L10 5.28z"
                            ></path>
                          </svg>
                        </div>
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 7 10">
                            <title>platform_phone_transp</title>
                            <path
                              d="M2.5 8.125a.624.624 0 101.249.001.624.624 0 00-1.249 0zM0 .938v8.125C0 9.58.42 10 .938 10h4.375c.517 0 .937-.42.937-.937V.938A.938.938 0 005.312 0H.938A.938.938 0 000 .938zm.938 8.007v-7.89c0-.065.052-.117.117-.117h4.14c.065 0 .117.052.117.117v7.89a.118.118 0 01-.117.118h-4.14a.118.118 0 01-.117-.118z"
                            ></path>
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltd64089e018c89048/615a85a49c76234dd174c199/Wildrift.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="LOL: WILD RIFT"
                    title="LOL: WILD RIFT"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(160, 193, 236) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt047f894a4d0e8fed/615a85216d2d465121b1c108/WildRift.svg?"
                          alt="LOL: WILD RIFT"
                          title="LOL: WILD RIFT"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>LEAGUE OF LEGENDS, NOW ON MOBILE</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt">
                      <div class="GHMgBnj6lwMEIU-yFlqCs">
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 7 10">
                            <title>platform_phone_transp</title>
                            <path
                              d="M2.5 8.125a.624.624 0 101.249.001.624.624 0 00-1.249 0zM0 .938v8.125C0 9.58.42 10 .938 10h4.375c.517 0 .937-.42.937-.937V.938A.938.938 0 005.312 0H.938A.938.938 0 000 .938zm.938 8.007v-7.89c0-.065.052-.117.117-.117h4.14c.065 0 .117.052.117.117v7.89a.118.118 0 01-.117.118h-4.14a.118.118 0 01-.117-.118z"
                            ></path>
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt15a80d65a2698d1f/615a859d8f1f7b55821485ee/convergence.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="CONV/RGENCE"
                    title="CONV/RGENCE"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(173, 110, 137) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt07a59d6098466b37/615a8d7df2882661476b6adb/convergence-logo.png?"
                          alt="CONV/RGENCE"
                          title="CONV/RGENCE"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>EXPLORE ZAUN AS EKKO IN THIS ACTION PLATFORMER</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt8589cd81c00f5c6a/6189ee6d666f1777c9bcfa52/JFG_Key_Art_T2AV2.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="HEXTECH MAYHEM"
                    title="HEXTECH MAYHEM"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(172, 76, 84) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt589f0c88c9f4fe5c/618d9795867d1817d95f3b15/HM.svg?"
                          alt="HEXTECH MAYHEM"
                          title="HEXTECH MAYHEM"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>Riot Forge Presents Hextech Mayhem</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt">
                      <div class="GHMgBnj6lwMEIU-yFlqCs">
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 10 10">
                            <title>platform_windows_transp</title>
                            <path
                              d="M0 1.416L4.087.86l.002 3.929-4.084.023L0 1.416zm4.085 3.827l.003 3.933-4.085-.56V5.218l4.082.026zM4.58.79L9.998 0v4.741l-5.418.042V.79zM10 5.279L9.998 10 4.58 9.238l-.008-3.966L10 5.28z"
                            ></path>
                          </svg>
                        </div>
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 7 10">
                            <title>platform_phone_transp</title>
                            <path
                              d="M2.5 8.125a.624.624 0 101.249.001.624.624 0 00-1.249 0zM0 .938v8.125C0 9.58.42 10 .938 10h4.375c.517 0 .937-.42.937-.937V.938A.938.938 0 005.312 0H.938A.938.938 0 000 .938zm.938 8.007v-7.89c0-.065.052-.117.117-.117h4.14c.065 0 .117.052.117.117v7.89a.118.118 0 01-.117.118h-4.14a.118.118 0 01-.117-.118z"
                            ></path>
                          </svg>
                        </div>
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 11 10">
                            <title>platform_switch_transp</title>
                            <path
                              d="M3.015.033a2.584 2.584 0 00-2.05 1.884c-.09.35-.097.555-.086 3.27.006 2.492.008 2.55.05 2.742.23 1.038.966 1.777 2.014 2.021.137.031.31.038 1.43.044 1.16.008 1.28.006 1.311-.025.031-.031.033-.43.033-4.961 0-3.358-.006-4.94-.02-4.97C5.676.003 5.64 0 4.427.003c-.985.002-1.281.008-1.412.03zM4.89 5.002v4.195l-.842-.01c-.777-.009-.86-.013-1.015-.052a1.756 1.756 0 01-1.3-1.355c-.046-.209-.046-5.36-.002-5.565A1.778 1.778 0 012.802.933c.273-.11.4-.122 1.286-.124l.801-.002v4.195z"
                              fill="#7E7E7E"
                            ></path>
                            <path
                              d="M3.193 2.074c-.13.025-.329.124-.434.217-.218.188-.325.456-.309.77a.651.651 0 00.085.34c.097.2.244.348.445.447a.643.643 0 00.354.083c.164.006.222 0 .332-.037.449-.152.72-.588.643-1.036a.951.951 0 00-1.116-.784z"
                              fill="#7E7E7E"
                            ></path>
                            <path
                              d="M6.726.015c-.009.006-.015 2.25-.015 4.987 0 4.516.002 4.974.033 4.986.056.02 1.663.013 1.862-.008a2.585 2.585 0 002.14-1.729c.131-.39.127-.286.127-3.261 0-2.375-.004-2.729-.033-2.88A2.57 2.57 0 008.732.03C8.587.005 8.363 0 7.642 0c-.496 0-.91.005-.916.014zm2.21 4.51c.324.084.589.33.697.645.068.195.066.48-.002.659a1.022 1.022 0 01-.694.641 1.02 1.02 0 01-1.22-.691 1.187 1.187 0 01.009-.584 1.005 1.005 0 011.21-.67z"
                            ></path>
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt7b361b63541962b6/63e56f590773755832f894cf/MAGESEEKER-PRODUCT-IMAGE-1920x1080.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="THE MAGESEEKER"
                    title="THE MAGESEEKER"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(57, 49, 76) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blte903a9feb702cb91/63e56f7dfb32ec1b0e9c93e7/Mageseeker_Logo_TM_Vector_White.png?"
                          alt="THE MAGESEEKER"
                          title="THE MAGESEEKER"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span
                        >PLAY AS SYLAS AND LIBERATE DEMACIA FROM TYRANNY IN THIS ACTION RPG</span
                      >
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt">
                      <div class="GHMgBnj6lwMEIU-yFlqCs">
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 10 10">
                            <title>platform_windows_transp</title>
                            <path
                              d="M0 1.416L4.087.86l.002 3.929-4.084.023L0 1.416zm4.085 3.827l.003 3.933-4.085-.56V5.218l4.082.026zM4.58.79L9.998 0v4.741l-5.418.042V.79zM10 5.279L9.998 10 4.58 9.238l-.008-3.966L10 5.28z"
                            ></path>
                          </svg>
                        </div>
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 11 10">
                            <title>platform_switch_transp</title>
                            <path
                              d="M3.015.033a2.584 2.584 0 00-2.05 1.884c-.09.35-.097.555-.086 3.27.006 2.492.008 2.55.05 2.742.23 1.038.966 1.777 2.014 2.021.137.031.31.038 1.43.044 1.16.008 1.28.006 1.311-.025.031-.031.033-.43.033-4.961 0-3.358-.006-4.94-.02-4.97C5.676.003 5.64 0 4.427.003c-.985.002-1.281.008-1.412.03zM4.89 5.002v4.195l-.842-.01c-.777-.009-.86-.013-1.015-.052a1.756 1.756 0 01-1.3-1.355c-.046-.209-.046-5.36-.002-5.565A1.778 1.778 0 012.802.933c.273-.11.4-.122 1.286-.124l.801-.002v4.195z"
                              fill="#7E7E7E"
                            ></path>
                            <path
                              d="M3.193 2.074c-.13.025-.329.124-.434.217-.218.188-.325.456-.309.77a.651.651 0 00.085.34c.097.2.244.348.445.447a.643.643 0 00.354.083c.164.006.222 0 .332-.037.449-.152.72-.588.643-1.036a.951.951 0 00-1.116-.784z"
                              fill="#7E7E7E"
                            ></path>
                            <path
                              d="M6.726.015c-.009.006-.015 2.25-.015 4.987 0 4.516.002 4.974.033 4.986.056.02 1.663.013 1.862-.008a2.585 2.585 0 002.14-1.729c.131-.39.127-.286.127-3.261 0-2.375-.004-2.729-.033-2.88A2.57 2.57 0 008.732.03C8.587.005 8.363 0 7.642 0c-.496 0-.91.005-.916.014zm2.21 4.51c.324.084.589.33.697.645.068.195.066.48-.002.659a1.022 1.022 0 01-.694.641 1.02 1.02 0 01-1.22-.691 1.187 1.187 0 01.009-.584 1.005 1.005 0 011.21-.67z"
                            ></path>
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt160d084323f31a63/615a859c7ab23a526f225189/ruined_king.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="RUINED KING"
                    title="RUINED KING"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(116, 193, 175) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt3b981873fd7d9af2/615a8521c34d415711f7e1da/Ruined_King.svg?"
                          alt="RUINED KING"
                          title="RUINED KING"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>RISE AGAINST RUIN IN THIS TURN BASED RPG</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt">
                      <div class="GHMgBnj6lwMEIU-yFlqCs">
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 10 10">
                            <title>platform_windows_transp</title>
                            <path
                              d="M0 1.416L4.087.86l.002 3.929-4.084.023L0 1.416zm4.085 3.827l.003 3.933-4.085-.56V5.218l4.082.026zM4.58.79L9.998 0v4.741l-5.418.042V.79zM10 5.279L9.998 10 4.58 9.238l-.008-3.966L10 5.28z"
                            ></path>
                          </svg>
                        </div>
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 11 10">
                            <title>platform_switch_transp</title>
                            <path
                              d="M3.015.033a2.584 2.584 0 00-2.05 1.884c-.09.35-.097.555-.086 3.27.006 2.492.008 2.55.05 2.742.23 1.038.966 1.777 2.014 2.021.137.031.31.038 1.43.044 1.16.008 1.28.006 1.311-.025.031-.031.033-.43.033-4.961 0-3.358-.006-4.94-.02-4.97C5.676.003 5.64 0 4.427.003c-.985.002-1.281.008-1.412.03zM4.89 5.002v4.195l-.842-.01c-.777-.009-.86-.013-1.015-.052a1.756 1.756 0 01-1.3-1.355c-.046-.209-.046-5.36-.002-5.565A1.778 1.778 0 012.802.933c.273-.11.4-.122 1.286-.124l.801-.002v4.195z"
                              fill="#7E7E7E"
                            ></path>
                            <path
                              d="M3.193 2.074c-.13.025-.329.124-.434.217-.218.188-.325.456-.309.77a.651.651 0 00.085.34c.097.2.244.348.445.447a.643.643 0 00.354.083c.164.006.222 0 .332-.037.449-.152.72-.588.643-1.036a.951.951 0 00-1.116-.784z"
                              fill="#7E7E7E"
                            ></path>
                            <path
                              d="M6.726.015c-.009.006-.015 2.25-.015 4.987 0 4.516.002 4.974.033 4.986.056.02 1.663.013 1.862-.008a2.585 2.585 0 002.14-1.729c.131-.39.127-.286.127-3.261 0-2.375-.004-2.729-.033-2.88A2.57 2.57 0 008.732.03C8.587.005 8.363 0 7.642 0c-.496 0-.91.005-.916.014zm2.21 4.51c.324.084.589.33.697.645.068.195.066.48-.002.659a1.022 1.022 0 01-.694.641 1.02 1.02 0 01-1.22-.691 1.187 1.187 0 01.009-.584 1.005 1.005 0 011.21-.67z"
                            ></path>
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltf9eb503252c8233e/6192ffed4ce2b23a1fb3c548/Everson_KeyArt01.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="SONG OF NUNU"
                    title="SONG OF NUNU"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(66, 88, 166) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt3e9708c7299d2f5a/61af12f9a342a65863542661/songofnunu-logotype.png?"
                          alt="SONG OF NUNU"
                          title="SONG OF NUNU"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>A Song Lives Forever</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt">
                      <div class="GHMgBnj6lwMEIU-yFlqCs">
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 10 10">
                            <title>platform_windows_transp</title>
                            <path
                              d="M0 1.416L4.087.86l.002 3.929-4.084.023L0 1.416zm4.085 3.827l.003 3.933-4.085-.56V5.218l4.082.026zM4.58.79L9.998 0v4.741l-5.418.042V.79zM10 5.279L9.998 10 4.58 9.238l-.008-3.966L10 5.28z"
                            ></path>
                          </svg>
                        </div>
                        <div class="">
                          <svg width="8" height="8" class="" viewBox="0 0 11 10">
                            <title>platform_switch_transp</title>
                            <path
                              d="M3.015.033a2.584 2.584 0 00-2.05 1.884c-.09.35-.097.555-.086 3.27.006 2.492.008 2.55.05 2.742.23 1.038.966 1.777 2.014 2.021.137.031.31.038 1.43.044 1.16.008 1.28.006 1.311-.025.031-.031.033-.43.033-4.961 0-3.358-.006-4.94-.02-4.97C5.676.003 5.64 0 4.427.003c-.985.002-1.281.008-1.412.03zM4.89 5.002v4.195l-.842-.01c-.777-.009-.86-.013-1.015-.052a1.756 1.756 0 01-1.3-1.355c-.046-.209-.046-5.36-.002-5.565A1.778 1.778 0 012.802.933c.273-.11.4-.122 1.286-.124l.801-.002v4.195z"
                              fill="#7E7E7E"
                            ></path>
                            <path
                              d="M3.193 2.074c-.13.025-.329.124-.434.217-.218.188-.325.456-.309.77a.651.651 0 00.085.34c.097.2.244.348.445.447a.643.643 0 00.354.083c.164.006.222 0 .332-.037.449-.152.72-.588.643-1.036a.951.951 0 00-1.116-.784z"
                              fill="#7E7E7E"
                            ></path>
                            <path
                              d="M6.726.015c-.009.006-.015 2.25-.015 4.987 0 4.516.002 4.974.033 4.986.056.02 1.663.013 1.862-.008a2.585 2.585 0 002.14-1.729c.131-.39.127-.286.127-3.261 0-2.375-.004-2.729-.033-2.88A2.57 2.57 0 008.732.03C8.587.005 8.363 0 7.642 0c-.496 0-.91.005-.916.014zm2.21 4.51c.324.084.589.33.697.645.068.195.066.48-.002.659a1.022 1.022 0 01-.694.641 1.02 1.02 0 01-1.22-.691 1.187 1.187 0 01.009-.584 1.005 1.005 0 011.21-.67z"
                            ></path>
                          </svg>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt8e6f343314f438ee/615d4fd6f2882661476b77da/Riot_Forge.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="RIOT FORGE GAMES"
                    title="RIOT FORGE GAMES"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(48, 76, 64) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt311c430e578b5709/615a85179c76234dd174c189/Riot_Forge.svg?"
                          alt="RIOT FORGE GAMES"
                          title="RIOT FORGE GAMES"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>PUBLISHER OF COMPLETABLE EXPERIENCES FROM THE LEAGUE UNIVERSE</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blta3add1f2553033a2/6424cbeb223f2f118c954ad5/033023_LoL_Esports_MegaMenu_Product_Card.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="LOL ESPORTS"
                    title="LOL ESPORTS"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(90, 190, 205) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt79e09e13810b1131/6424e722cc01de1087082bc5/033023_LoL_Logo_White.png?"
                          alt="LOL ESPORTS"
                          title="LOL ESPORTS"
                        /> -->
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt42e1162ed54d15d2/6424cbeb18bad210b77f86b7/033023_VCT_Esports_MegaMenu_Product_Card.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="VALORANT ESPORTS"
                    title="VALORANT ESPORTS"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(147, 34, 28) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt897524cd0f07ccbd/6424e722167b14113bedf6b8/033023_VCT23_Logo_White.png?"
                          alt="VALORANT ESPORTS"
                          title="VALORANT ESPORTS"
                        /> -->
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blta84d6d394801dedb/615a859d9c76234dd174c195/arcane.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="ARCANE"
                    title="ARCANE"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(43, 61, 109) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltd307b99a6713cbe9/615a8517a4d10c511f1ad399/arcane.svg?"
                          alt="ARCANE"
                          title="ARCANE"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>AN ANIMATED SERIES ON NETFLIX FROM THE WORLD OF LEAGUE OF LEGENDS</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltea74e94e1296b057/615a8fccc22cd45706cf29fe/universe.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="UNIVERSE"
                    title="UNIVERSE"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(35, 83, 87) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <span>UNIVERSE</span>
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>THE DEFINITIVE SOURCE FOR THE WORLD OF LEAGUE OF LEGENDS</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt4303739f818a50e3/615a859d054fcd4c567205ab/Riot_Music.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="RIOT GAMES MUSIC"
                    title="RIOT GAMES MUSIC"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(121, 49, 123) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <span>RIOT GAMES MUSIC</span>
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>MUSIC HAS A NEW HOME</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltf2aeb4512fc8f095/615a859ddb34085ff954a028/Riot_Games.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="RIOT GAMES"
                    title="RIOT GAMES"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(212, 190, 179) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltaa12e735bcd4f9a8/6217f2125fe07272a8a24985/RG-2022.svg?"
                          alt="RIOT GAMES"
                          title="RIOT GAMES"
                        /> -->
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>UNLEASH PLAY</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt1313d1f5e9424233/615a859d7ab23a526f22518d/Riot_Merch.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="RIOT MERCH"
                    title="RIOT MERCH"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(0, 61, 90) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <span>RIOT MERCH</span>
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>THE OFFICIAL HOME OF RIOT GAMES MERCH</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltb984b7fd7649c9b0/615a93758f1f7b5582148611/riot-mobile.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="RIOT MOBILE"
                    title="RIOT MOBILE"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(252, 63, 67) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <span>RIOT MOBILE</span>
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>YOUR MOBILE COMPANION FOR ALL THINGS RIOT GAMES</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_1VwbTRUieUR90wWqaSBvLx riotbar-application-switcher-menu-product-card-wrapper"
              >
                <div class="_25lcxhlJ8jAlSNFn2l6PjD"></div>
                <!-- <img
                    class="_2vBqj2b0PZ3_l_JDGbzr0O"
                    src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltb67b232cf8d5069f/617b29d861f3c21067237706/riot-support-2.jpg??&amp;format=pjpg&amp;quality=85"
                    alt="RIOT SUPPORT"
                    title="RIOT SUPPORT"
                  /> -->
                <div
                  class="l2TgTYRG5vgtqKacZs3zt"
                  style="
                    background-image: radial-gradient(
                      160.43% 179.54% at 100.43% 100%,
                      rgb(234, 0, 40) 0%,
                      rgb(10, 10, 10) 70%
                    );
                  "
                >
                  <div class="_3PlPzDfCaurVFlaUUkTCy2">
                    <div
                      class="_2M4zY1K28k5fl-TJUheEda riotbar-application-switcher-menu-product-card-frame-title"
                    >
                      <span>RIOT SUPPORT</span>
                    </div>
                    <div
                      id="riotbar-application-switcher-menu-product-card-frame-description"
                      class="QXXXxaa5y9OFgod_DbdsF"
                    >
                      <span>FROM TECH TO TILT, WE’RE HERE TO HELP YOU</span>
                    </div>
                    <div class="_2pcY7uH3fjuYGCFH3bbupt"></div>
                  </div>
                </div>
              </div>
              <div
                class="_3YsJ6HEwtO6SEa3XrP5v-H riotbar-application-switcher-card-components-wrapper"
              >
                <div
                  class="_2eiNMPH70IHZfJB-zKtOky _2eiNMPH70IHZfJB-zKtOky riotbar-application-switcher-card"
                >
                  <a
                    href="https://playvalorant.com/en-us/news/game-updates/defy-definition-episode-7-act-1/?utm_medium=promo2%2Bwww.riotgames.com&amp;utm_source=riotbar"
                    target="_blank"
                    data-interaction-id="riotbar_app-switcher-promo_card2"
                    ><div class="undefined riotbar-application-card-image-wrapper">
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/blt7ea5564832d87165/64966337b70242984bcab3a8/062723_Ep7_Riot_Bar_Promo_card_660x428.png??&amp;format=pjpg&amp;quality=85"
                          alt="Check out how VALORANT’s evolving the game in this new Episode."
                          title="Check out how VALORANT’s evolving the game in this new Episode."
                        /> -->
                    </div>
                    <div class="_3mN3WworaolNDXLcDGxz2V riotbar-application-card-title-wrapper">
                      <h4>Check out how VALORANT’s evolving the game in this new Episode.</h4>
                    </div></a
                  >
                </div>
                <div
                  class="_2eiNMPH70IHZfJB-zKtOky _2eiNMPH70IHZfJB-zKtOky riotbar-application-switcher-card"
                >
                  <a
                    href="https://playruneterra.com/?utm_medium=promo3%2Bwww.riotgames.com&amp;utm_source=riotbar"
                    target="_blank"
                    data-interaction-id="riotbar_app-switcher-promo_card3"
                    ><div class="undefined riotbar-application-card-image-wrapper">
                      <!-- <img
                          src="https://images.contentstack.io/v3/assets/blt0eb2a2986b796d29/bltc9637bfbdae4ff91/649b449305ac38d3b5aebb85/LLoR_7B2023_HotH_RiotBarApplicationSwitcher_660x428.jpg??&amp;format=pjpg&amp;quality=85"
                          alt="New Legends of Runeterra Expansion - Heart of the Huntress"
                          title="New Legends of Runeterra Expansion - Heart of the Huntress"
                        /> -->
                    </div>
                    <div class="_3mN3WworaolNDXLcDGxz2V riotbar-application-card-title-wrapper">
                      <h4>New Legends of Runeterra Expansion - Heart of the Huntress</h4>
                    </div></a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <slot></slot>
    </div>
  </div>
  <button @click.native="showTrojkat()">klik.native</button>
</template>

<script>
import { ref, defineComponent } from 'vue'
export default defineComponent({
  name: 'WelcomeItem',
  setup() {
    const trojkatDisplayBlock = ref(false)
    const section1 = ref([
      {
        headerName: 'GAMES',
        array: [
          {
            href: 'https://www.leagueoflegends.com/en-us/?utm_medium=card1%2Bwww.riotgames.com&amp;utm_source=riotbar',
            content: 'Face off in the ultimate 5v5 battle arena',
            title: 'LEAGUE OF LEGENDS'
          },

          {
            href: 'https://playvalorant.com/en-us/?utm_source=riotbar&amp;utm_medium=productcard%2Bwww.riotgames.com&amp;utm_campaign=val&amp;utm_content=ep7act1',
            content: 'Style on your enemies in this 5v5 tactical shooter',
            title: 'VALORANT'
          },
          {
            href: 'https://teamfighttactics.leagueoflegends.com/en-us/?utm_medium=card3%2Bwww.riotgames.com&amp;utm_source=riotbar',
            content: 'A TEAM-BUILDING BATTLE OF WITS',
            title: 'TEAMFIGHT TACTICS'
          },
          {
            href: 'https://playruneterra.com/en-us/?utm_medium=card4%2Bwww.riotgames.com&amp;utm_source=riotbar',
            content: 'Master every moment in this strategy card game',
            title: 'LEGENDS OF RUNETERRA'
          },
          {
            href: 'https://wildrift.leagueoflegends.com/en-us/?utm_medium=card5%2Bwww.riotgames.com&amp;utm_source=riotbar',
            content: 'LEAGUE OF LEGENDS, NOW ON MOBILE',
            title: 'LOL: WILD RIFT'
          }
        ]
      },
      { headerName: '' },
      { headerName: '' }
    ])
    const section1A = section1.value[0].array
    return {
      trojkatDisplayBlock,
      section1A
    }
  },
  mounted() {},
  methods: {
    showTrojkat() {
      // const widtTrojkat2 = document.querySelector('.trojkat2')
      // console.log(widtTrojkat2, 'widtTrojkat2 h hh h ')
      // // widtTrojkat2.style.
      console.log('cokolwiek')
      this.trojkatDisplayBlock = !this.trojkatDisplayBlock
    }
  }
})
</script>

<style scoped>
@keyframes animowanyTrojkat {
  0% {
    z-index: 2;
    clip-path: polygon(0 0, 100% 0%, 100% 80px, 25% 80px, 0 80px);
    background-color: blue;
  }
  50% {
    clip-path: polygon(0 0, 100% 0%, 100% 40%, 25% 70%, 0 40%);
  }
  100% {
    height: 100%;
    clip-path: polygon(0 0, 100% 0%, 100% 100%, 25% 100%, 0 100%);
    background-color: red;
  }
  0% {
    z-index: 0;
  }
}
.figury {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 700px;
  background-color: red;
  z-index: 0;
  animation: animowanyTrojkat 0.5s forwards linear;
}
.trojkat1 {
  width: 0px;
  height: 0px;
  border-right: 500px solid green;
  border-left: 0px solid transparent;
  border-bottom: 96px solid transparent;
  margin: 0 0;
}
.trojkat2 {
  width: 0px;
  height: 0px;
  border-left: 700px solid green;
  border-right: 0px solid transparent;
  border-bottom: 96px solid transparent;
  margin: 0 0;
}
.item {
  margin-top: 2rem;
  display: flex;
}

.details {
  flex: 1;
  /* margin-left: 1rem; */
}

i {
  display: flex;
  place-items: center;
  place-content: center;
  width: 32px;
  height: 32px;
  color: var(--color-text);
}

h3 {
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}

@media (min-width: 1024px) {
  .item {
    margin-top: 0;
    padding: 0.4rem 0 1rem calc(var(--section-gap) / 2);
  }

  i {
    top: calc(50% - 25px);
    left: -26px;
    position: absolute;
    border: 1px solid var(--color-border);
    background: var(--color-background);
    border-radius: 8px;
    width: 50px;
    height: 50px;
  }

  .item:before {
    content: ' ';
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    bottom: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:after {
    content: ' ';
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    top: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:first-of-type:before {
    display: none;
  }

  .item:last-of-type:after {
    display: none;
  }
}
</style>
