#' Create a matrix
#'
#' @param n_row customize the matrix size by row number
#' @param n_col customize the matrix size by column number
#' @param set_mean customize the mean while generating the random number
#' @param set_sd customize the standard deviation while generating the random number
#'
#' @return A matrix
#' @export
#'
#' @examples
#' x <- random_matrix(n_row = 3, n_col = 5, set_mean = 0, set_sd = 1)


random_matrix <- function(n_row = 2, n_col = 2, set_mean =0, set_sd =5) {
  data_number <- n_row*n_col
  ini_matrix <- matrix(data = rnorm(data_number, mean = set_mean, sd = set_sd), nrow = n_row, ncol = n_col)
  ini_matrix
}
