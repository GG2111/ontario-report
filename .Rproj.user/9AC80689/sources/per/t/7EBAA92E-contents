library(tidyverse)
sample_data <- read_csv("sample_data.csv")
read_csv(file = 'sample_data.csv')
ggplot(data=sample_data)


ggplot(data = sample_data) +
  aes(x = total_nitrogen) +
  labs(x = "total nitrogen (mg/L)") +
  aes(y = cells_per_ml) +
  labs(y = "Cells per mL") +
  geom_point() +
  labs(title = "Does total nitrogen affect microbial abundance?")


ggplot(data = sample_data) +
  aes(x = total_nitrogen) +
  labs(x = "total nitrogen (mg/L)") +
  aes(y = cells_per_ml/1000000) +
  labs(y = "Cells per mL") +
  geom_point() +
  labs(title = "Does total nitrogen affect microbial abundance?")

ggplot(data = sample_data) +
  aes(x = total_nitrogen) +
  labs(x = "total nitrogen (mg/L)") +
  aes(y = cells_per_ml/1000000) +
  labs(y = "Cells per mL") +
  geom_line() +
  labs(title = "Does total nitrogen affect microbial abundance?")

ggplot(data = sample_data) +
  aes(x = total_nitrogen) +
  labs(x = "total nitrogen (µg N/L)") +
  aes(y = cells_per_ml/1000000) +
  labs(y = "Cells (milion/ mL") +
  geom_smooth() +
  labs(title = "Does total nitrogen affect microbial abundance?") + 
  aes(color = env_group) +
  aes(size = temperature) +
  labs (size = "Temperature (C)", color = "Environmental Group")

ggsave("ass_plot#1.png", width=6, height=4)

ggsave("ass_plot#1.png", width=6, height=4)

ggplot(data = sample_data) +
  aes(x = total_phosphorus) +
  labs(x = "total nitrogen (µg N/L)") +
  aes(y = cells_per_ml/1000000) +
  labs(y = "Cells (milion/ mL") +
  geom_smooth() +
  labs(title = "Does total nitrogen affect microbial abundance?") +
  aes(color = env_group) +
  aes(size = temperature) +
  labs (size = "Temperature (C)", color = "Environmental Group")

ggsave("ass_plot#2.png", width=6, height=4)

ggplot(data = sample_data) +
  aes(x = total_phosphorus) +
  labs(x = "total phosphorus ( µg P/L)") +
  aes(y = cells_per_ml/1000000) +
  labs(y = "Cells (milion/ mL") +
  geom_smooth() +
  labs(title = "Does total phosphorus affect microbial abundance?") +
  aes(color = env_group) +
  aes(size = temperature) +
  labs (size = "Temperature (C)", color = "Environmental Group")
ggsave("ass_plot#2.png", width=6, height=4)


ggplot(data = sample_data) +
  aes(x = total_nitrogen) +
  labs(x = "total nitrogen (µg N/L)") +
  aes(y = cells_per_ml/1000000) +
  labs(y = "Cells (milion/ mL") +
  geom_smooth() +
  labs(title = "Does total nitrogen affect microbial abundance?") + 
  aes(color = env_group) +
  aes(size = temperature) +
  labs (size = "Temperature (C)", color = "Environmental Group")

ggsave("ass_plot#1.png", width=6, height=4)




