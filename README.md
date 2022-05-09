# V_debug_diary

# return index of element
label_ = np.random.choice(2, int(n_), replace=True, p=[0.5, 0.5])
index_0_ = np.transpose(np.array((label_ == 0).nonzero()))
index_1_ = np.transpose(np.array((label_ == 1).nonzero()))
print(index_0_.shape)
n_0_ = index_0_.shape[0]
n_1_ = index_1_.shape[0]
