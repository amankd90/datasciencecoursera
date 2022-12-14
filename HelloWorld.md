## This is a markdown file

hw <- read.csv(file="C:/Users/akaur/Downloads/Coursera-DS/quiz1_data/hw1_data.csv")
hw


lastrow = tail (hw, n=2)
lastrow

a = hw[47,]
print(a)
#testing new today
summary(hw)

mean(hw$Ozone)

sub <- subset (hw, Ozone > 31 & Temp > 90)
sub

summary(sub)

sub2 <- subset (hw, Month==6)
sub2
summary(sub2)

sub3 <- subset (hw, Month==5)
sub3
summary(sub3)
args(mean)


x <- c("a", "b", "c", "d")
for(i in 1:4) {
print(x[i])
}
for(i in seq_along(x)) {
print(x[i])
}
for(letter in x) {
print(letter)
}
for(i in 1:4) print(x[i])
