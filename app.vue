Vue.createApp({
	data() {
		return {
			monthlyCost: {
				zius: {
					template:1100,
					customize:4400,
					original:6600,
					shopping:6600,
				},
				server: 1320,
				ssl: 800, //need to confirm the fee
			},
			initCost: {
				zius: 30000,
				server: 0,
				ssl: 880,
			},
			yearlyCost: {
				domain: 1650,
			},
		};
	},
}).mount('#pricingCalculator');
