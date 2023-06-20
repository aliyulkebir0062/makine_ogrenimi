import pandas

data={
    "kalori":[420,320,180],
    "sure":[60,40,25]
}
#tümverileriyazmaişlemi
##ctrl+k+c yorum satırına çevirme
##ctrl+k+u kodu devreye alma
data=pandas.read_csv("data.csv")
#df=pandas.DataFrame(data)
# df=pandas.DataFrame(data,index=["1.gün","2.gün","3.gün"])
# pandas.options.display.max_rows=30
print(data["Calories"])
#tek sütun
#print(df.loc[0])
###data["Motivasyon"]=data.Calories+""+data.Duration

#data.rename(columns={"Duration":"Zaman"})

print(data.rename(columns={"Duration":"Zaman"}))
