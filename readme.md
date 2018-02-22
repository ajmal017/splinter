# Splinter

Splinter is a back-testing framework to test various strategies across cryptocurrencies.

The name has come from the Ninja Turtles trainer, Splinter:  

![Image of Splinter](http://cdn2-www.superherohype.com/assets/uploads/2012/06/file_171063_8_1832775-bow.jpg)

## Roadmap  
- [x] Get source of data  
- [ ] Create structure for strategy testing  
- [X] Create basic/easy to use variables (like Trading View)  
- [ ] Be able to back test any date range with different time units (1h, 2h, 4h, 8h, 12h, 1d)  
- [ ] Create easy rules:  
	- [ ] "total active trades"  
	- [ ] "max units in a position"
	- [ ] "max units in a pair"
- [ ] Easily create Stop-Loss
- [ ] Create Sell-Limit Orders
- [ ] Create ease of back-testing
	- [X] Specify pair, date-range, strategy
	- [ ] Return 
		- [ ] % up or down
		- [ ] % drawdown
		- [ ] # of trades
		- [ ] # of successful trades
		- [ ] # of failed trades
		- [ ] # median/avg of each successful failed trade
	- [ ] Store all information in the database
	- [ ] Create system to send alerts
	- [ ] Create system to enact trades
	- [ ] Create twitter sentiment analysis system
	- [ ] Create ML or DL integration
