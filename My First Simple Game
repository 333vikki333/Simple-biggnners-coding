import streamlit as st
import random

def main():
    st.title("Enjoy the Rock Paper Scissors Game")

    # Define the choices
    choices = ["Rock", "Paper", "Scissors"]

    # Player choice
    player_choice = st.selectbox("Choose your move:", choices)

    # Button to submit the choice
    if st.button("Play"):
        computer_choice = random.choice(choices)
        st.write(f"Computer chose: {computer_choice}")

        # Determine the winner
        if player_choice == computer_choice:
            st.write("It's a tie!")
        elif (player_choice == "Rock" and computer_choice == "Scissors") or \
             (player_choice == "Paper" and computer_choice == "Rock") or \
             (player_choice == "Scissors" and computer_choice == "Paper"):
            st.write("You win!")
        else:
            st.write("Computer wins!")

if __name__ == "__main__":
    main()



