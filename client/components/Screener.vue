<template lang="pug">
.table
  .table-header
    .table-header__toolbar
      .dropdown
        .dropdown-button
          .dropdown-button__name
          .dropdown-button__icon
        .dropdown-modal
      .dropdown
        .dropdown-button--icon
          .dropdown-button__name
          .dropdown-button__icon
        .dropdown-modal
      .dropdown
        .dropdown-button
          .dropdown-button__name
          .dropdown-button__icon
        .dropdown-modal
      .dropdown
        .dropdown-button
          .dropdown-button__name
          .dropdown-button__icon
        .dropdown-modal
      .dropdown
        .dropdown-button--filter
          .dropdown-button__name
          .dropdown-button__icon
        .dropdown-modal
    .table-header__title
      .title--ascending
        .title__name
        .title__subname
        .title__conf
      .title--descending
        .title__name
        .title__subname
        .title__conf
      .title
        .title__name
        .title__subname
        .title__conf
      .title
        .title__name
        .title__subname
        .title__conf
      .title
        .title__name
        .title__subname
        .title__conf
      .title--more
        .title__name
        .title__subname
        .title__conf
  .table-body
    .table-body__row
      .cell--left
        .cell__shortcut
        .cell__data        
      .cell
        .cell__data        
      .cell
        .cell__data             
      .cell
        .cell__data             
      .cell--left
        .cell__data        
</template>

<script>
export default {
  data() {
    return {
      table: {
        // 오버뷰
        // 마이너메이저 페어즈
        // 일반
        // 필터
        title: [
          "티커",
          "49 매치",
          "현재가",
          "변화 %",
          "체인지",
          "매수호가",
          "매도호가",
          "고가",
          "저가",
          "레이팅",
          "패턴"
        ],
        body: [
          {
            ticker: "AUDCHF",
            currentPrice: 0.65355,
            difference: -0.75,
            change: -0.00497,
            buyQuotes: 0.65355,
            sellQuotes: 0.65381,
            high: 0.65885,
            low: 0.65242,
            rating: "바이"
          },
          {
            ticker: "AUDEUR",
            currentPrice: 0.6116,
            difference: -0.66,
            change: -0.004,
            buyQuotes: 0.6116,
            sellQuotes: 0.612,
            high: 0.6157,
            low: 0.6109,
            rating: "바이"
          },
          {
            ticker: "GBPCHF",
            currentPrice: 1.18213,
            difference: -0.56,
            change: -0.00665,
            buyQuotes: 1.18219,
            sellQuotes: 1.18246,
            high: 1.18976,
            low: 1.1799,
            rating: "셀"
          },
          {
            ticker: "USDCHF",
            currentPrice: 0.89891,
            difference: -0.54,
            change: -0.00491,
            buyQuotes: 0.899,
            sellQuotes: 0.89905,
            high: 0.90566,
            low: 0.89826,
            rating: "스트롱셀"
          },
          {
            ticker: "CADCHF",
            currentPrice: 0.68979,
            difference: -0.48,
            change: -0.00331,
            buyQuotes: 0.68969,
            sellQuotes: 0.68991,
            high: 0.69353,
            low: 0.68801,
            rating: "셀"
          },
          {
            ticker: "GBPEUR",
            currentPrice: 1.1066,
            difference: -0.45,
            change: -0.005,
            buyQuotes: 1.1066,
            sellQuotes: 1.1066,
            high: 1.1122,
            low: 1.1046,
            rating: "바이"
          },
          {
            ticker: "CADEUR",
            currentPrice: 0.6453,
            difference: -0.39,
            change: -0.0025,
            buyQuotes: 0.6453,
            sellQuotes: 0.6457,
            high: 0.648,
            low: 0.6444,
            rating: "바이"
          },
          {
            ticker: "AUDJPY",
            currentPrice: 75.088,
            difference: -0.33,
            change: -0.248,
            buyQuotes: 75.088,
            sellQuotes: 75.096,
            high: 75.377,
            low: 74.906,
            rating: "바이"
          }
        ]
      }
    };
  }
};
</script>

<style lang="sass" scoped></style>
