# import matplotlib.pyplot as plt
# import numpy as np
# import pandas
#
# x = [1,2,3,1,3,2]
# x = np.array([1,2,3,1,3,2])
# x = pd.Series(np.array([1,2,3,1,3,2]))
#
# plt.figure(figsize=(8,4)) # moxno yxasams aBHo wupuny u Geicomy 2paguxa (cmpouxa He o6a3ameneHa)
# plt.plot(x, linewidth=2, color='green', marker='*', linestyle='dashed', label='line_1')
#
# plt.legend() # noxasw6ams nezendy
#
# plt.grid(color="gray", linestyle=-'-', linewidth=1.5) # 6xamyume ompucoBKy cemku c onpedenenHumu napamempamu
# plt.yticks([0,0.5,1,1.5,2,2.5,3,3-5,4,4.5,5]) # moxHo AGHO yKa3amb, Kak nodnuceiGame oce
#
# plt.xticks()
#
# plt.xlabel('ocb a6cuncc')
#
# plt.ylabel('ocs opamnat');
#
# plt.show()

# import pandas
# import matplotlib.pyplot as plt
# import numpy as np
# x = np.linspace(0, 5, 50) # cosdaem maccu6 uz 100 4ucen float om @ do 5 c paBHomepHo6 wazom
# y = x*(x - 2) * (x - 4)
#
# plt.figure(figsize=(8,4)) # moxro yxasame a6Ho wupuny u Beicomy 2paguxka (cmpouKa He o6n3ameneHa)
# plt.scatter(x, y, label="line_1")
#
# plt.legend() # noxasviGame nezendy
#
# plt.grid(linewidth=1) # 6xauwume ompuco6ky cemku c onpedenenHemu napamempanu
#
# plt.yticks()
#
# plt.xticks()
#
# plt.xlabel('ocb a6cuncc')
#
# plt.ylabel('ocb opaunat')
#
# plt.show()

# import pandas
# import matplotlib.pyplot as plt
# import numpy as np
# # from pandas.tests.test_downstream import df
# #
# # features = ['wage', 'exper']
# # df[features].hist(figsize=(10, 4), bins=60);
# # plt.show()
# plt.pie(df.groupby('female')['wage'].count()); # круговая диаграмми (pie)
