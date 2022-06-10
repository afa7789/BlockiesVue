
<template>
	<div id="app">
		<VueBlockies
			v-for="item in items"
			:key="item"
			:seed="item"
			:size=8
			:scale=20
		/>
	</div>
</template>

<script>
import { defineComponent } from "vue";
// Uncomment import and local "components" registration if library is not registered globally.
// import { VueBlockies } from '@/entry.esm'; // 'vueblockies'

export default defineComponent({
	name: "Example",
	// components: {
	//  VueBlockies,
	// }
	data() {
		return {
			items: [
				"Monalisa",
				"0x0000000000000000000000000000000000000000000000000000000000000000",
				"Arthur F. Abeilice",
				"Vue.js is better then React",
				"Create the future you want",
				"Composition 8",
				"Royal Red and Blue",
				"Starry Night",
				"Beheading of Saint John the Baptist",
				"Guernica",
				"Night Watch",
				"The Persistence of Memory",
				"Luncheon on the Boating Party",
				"No. 5, 1948",
				"Water Lilies",
				"Landscape with the Fall of Icarus",
				"Las Meninas",
				"Three Musicians",
				"A Sunday Afternoon on the Island of La Grande Jatte",
				"Impression, Sunrise",
				"The Triumph of Galatea",
				"View of Toledo",
				"The Tower of Babel",
				"The Dance",
				"The Swing",
				"The Gleaners",
				"The Flower Carrier",
				"The Kiss",
				"Portrait de L’artiste Sans Barbe",
				"Whistler’s Mother",
				"Bal du Moulin de la Galette",
				"The Son of Man",
				"Cafe Terrace at Night",
				"American Gothic",
				"Les Demoiselles d’Avignon",
				"The Grand Odalisque",
				"The Liberty leading the people",
				"Napoleon crossing the Alps",
				"The Sleeping Gypsy",
				"Primavera",
				"Dogs Playing Poker",
				"Portrait of Dora Maar",
				"Massacre of the Innocents",
				"Portrait of Madame Recamier",
				"Sistine Chapel Ceiling",
				"The Birth of Venus",
				"The Arnolfini Marriage",
				"School of Athens",
				"Olympia",
				"The Third of May",
				"Creation of Adam",
				"The Scream",
				"The Last Supper",
				"Girl with a Pearl Earring",
			],
		};
	},
});
</script>

<style scoped>
#app {
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
	align-items: center;
}
</style>