# Swap-dai-usdc
Swap
#include <iostream>

void swapETHtoUSDT() {
    // Code to swap ETH to USDT
    std::cout << "Swapping ETH to USDT..." << std::endl;
    // API call or relevant logic for swapping ETH to USDT
}

void swapETHtoUSDC() {
    // Code to swap ETH to USDC
    std::cout << "Swapping ETH to USDC..." << std::endl;
    // API call or relevant logic for swapping ETH to USDC
}

void swapETHtoDAI() {
    // Code to swap ETH to DAI
    std::cout << "Swapping ETH to DAI..." << std::endl;
    // API call or relevant logic for swapping ETH to DAI
}

int main() {
    int swapOption;

    // Prompt the user to choose the swap option
    std::cout << "Choose the swap option:" << std::endl;
    std::cout << "1. ETH to USDT" << std::endl;
    std::cout << "2. ETH to USDC" << std::endl;
    std::cout << "3. ETH to DAI" << std::endl;
    std::cout << "Enter your choice (1-3): ";
    std::cin >> swapOption;

    // Perform the chosen swap
    switch (swapOption) {
        case 1:
            swapETHtoUSDT();
            break;
        case 2:
            swapETHtoUSDC();
            break;
        case 3:
            swapETHtoDAI();
            break;
        default:
            std::cout << "Invalid choice. Exiting..." << std::endl;
            return 0;
    }

    std::cout << "Swap completed successfully." << std::endl;

    return 0;
}
