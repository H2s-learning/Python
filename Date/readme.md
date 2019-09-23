Convert str into datetime

df['data'] = pd.to_datetime(df['data'], format='%Y-%m-%d')
