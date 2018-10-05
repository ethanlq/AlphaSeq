AlphaSeq: Sequence Discovery with Deep Reinforcement Learning (source code)

Abstract: Sequences play an important role in many applications and systems. Discovering sequences with desired properties has long been an interesting intellectual pursuit. This paper puts forth a new paradigm, AlphaSeq, to discover desired sequences algorithmically using deep reinforcement learning (DRL) techniques. AlphaSeq treats the sequence discovery problem as an episodic symbol-filling game, in which a player fills symbols in the vacant positions of a sequence set sequentially during an episode of the game. Each episode ends with a completely-filled sequence set, upon which a reward is given based on the desirability of the sequence set. AlphaSeq models the game as a Markov Decision Process (MDP), and adapts the DRL framework of AlphaGo to solve the MDP. Sequences discovered improve progressively as AlphaSeq, starting as a novice, learns to become an expert game player through many episodes of game playing. Compared with traditional sequence construction by mathematical tools, AlphaSeq is particularly suitable for problems with complex objectives intractable to mathematical analysis. We demonstrate the searching capabilities of AlphaSeq in two applications: 1) AlphaSeq successfully rediscovers a set of ideal complementary codes that can zero-force all potential interferences in multi-carrier CDMA systems; 2) AlphaSeq discovers new sequences that triple the signal-to-interference ratio – benchmarked against the well-known Legendre sequence – of a mismatched filter estimator in pulse compression radar systems.
