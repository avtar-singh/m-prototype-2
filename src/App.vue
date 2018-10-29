<template>
	<div id="app">
      <link rel="stylesheet" 
        href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" 
        integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" 
        crossorigin="anonymous">
      <link href="https://fonts.googleapis.com/css?family=Nunito+Sans" rel="stylesheet">
      <link href="https://fonts.googleapis.com/css?family=Abril+Fatface" rel="stylesheet">
      <link href="https://fonts.googleapis.com/css?family=Work+Sans:600" rel="stylesheet">
      <link href="https://fonts.googleapis.com/css?family=Acme" rel="stylesheet">
      <link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
      <Header></Header>
      <Container></Container>
      <Footer></Footer>
    </div>
</template>

<script>
import Vue from 'vue'
import Header from './components/Header'
import Container from './components/Container'
import Footer from './components/Footer'

	export default {
    name: 'app',
    components: { Header, Container, Footer }
  }
</script>

<style>
	#app {
    font-family: 'Nunito Sans', sans-serif;
    font-weight: normal;
    font-style: normal;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
	}
  .text-left{
    text-align: left;
  }
</style>