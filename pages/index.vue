<template>
  <div>
    <div id="main">
      <Profil />
      <div id="mainPage">
        <div id="intro">
          <Presentation />
          <hr />
          <Compteurs />
        </div>
        <APropos />
        <LastProjects />
        <Expertise />
        <AvisClients />
        <HireMeBottomIndex />
        <FooterPage />
      </div>
    </div>
  </div>
</template>

<style lang="scss">
#main {
  gap: 0px;
  display: flex;
  justify-content: center;
  margin: 0;
  padding: 122px 20px 0 20px;
  #mainPage {
    max-width: 900px;
    gap: 70px;
    display: flex;
    flex-direction: column;
    padding: 32px 0px 32px 0px;
    margin: 0 40px;
    flex: 1 1 auto;
    width: 100%;
  }
  hr {
    border: none;
    border-top: solid 1px rgba(221, 205, 195, 1);
    width: 100%;
  }
}

.navButton {
  display: flex;
  justify-content: center;
  align-items: center;
  background: rgba(23, 23, 23, 1);
  border-radius: 24px;
  padding: 6px 16px;
  gap: 6px;
  border: none;
  span {
    font-family: Plus Jakarta Sans;
    font-size: 14px;
    font-weight: 500;
    line-height: 20px;
    letter-spacing: 0em;
    text-align: center;
    color: white;
    margin: 0;
  }
}

#projectInfos {
  flex-wrap: wrap;
}
@media only screen and (max-width: 855px) {
  #main {
    flex-direction: column;
    align-items: center;
    justify-content: center;
    #mainPage {
      justify-content: center;
      align-items: center;
      margin: 0 25px;
    }
  }
}

</style>
